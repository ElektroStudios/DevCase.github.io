# ProfillingUtil.TestTimeAsync Method 
 

Asynchronously tests the execution of a Action and measures the elapsed time.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<TestExecutionInfo> TestTimeAsync(
	Action action
)
```

**VB**<br />
``` VB
Public Shared Function TestTimeAsync ( 
	action As Action
) As Task(Of TestExecutionInfo)
```

**VB Usage**<br />
``` VB Usage
Dim action As Action
Dim returnValue As Task(Of TestExecutionInfo)

returnValue = ProfillingUtil.TestTimeAsync(action)
```

**C++**<br />
``` C++
public:
static Task<TestExecutionInfo^>^ TestTimeAsync(
	Action^ action
)
```

**F#**<br />
``` F#
static member TestTimeAsync : 
        action : Action -> Task<TestExecutionInfo> 

```


#### Parameters
&nbsp;<dl><dt>action</dt><dd>Type: System.Action<br />The Action to invoke.</dd></dl>

#### Return Value
Type: Task(<a href="T_DevCase_Core_Diagnostics_TestExecutionInfo">TestExecutionInfo</a>)<br />An async Task(TResult) object that contains the result of the test.

## Examples
This is a code example. 
**VB**<br />
``` VB
Sub Test()

    Dim taskTestTime As Task(Of TestExecutionInfo) =
        TestTimeAsync(Sub()
                                         For x As Integer = 0 To 2500
                                             Console.WriteLine(x)
                                         Next x
                                     End Sub)

    taskTestTime.ContinueWith(Sub() Me.ShowTestExecutionInfo(taskTestTime.Result))

End Sub

Private Sub ShowTestExecutionInfo(ByVal teInfo As TestExecutionInfo)

    Dim sb As New Global.System.Text.StringBuilder
    Select Case teInfo.Success

        Case True
            With sb ' Set an information message.
                .AppendLine(String.Format("Method Name: {0}", teInfo.Method.Name))
                .AppendLine()
                .AppendLine(String.Format("Elapsed Time: {0}", teInfo.Elapsed.ToString("hh\:mm\:ss\:fff")))
            End With
            MessageBox.Show(sb.ToString(), "Code Execution Measurer", MessageBoxButtons.OK, MessageBoxIcon.Information)

        Case Else
            With sb ' Set an error message.
                .AppendLine("Exception occurred during code execution measuring.")
                .AppendLine()
                .AppendLine(String.Format("Method Name: {0}", teInfo.Method.Name))
                .AppendLine()
                .AppendLine(String.Format("Exception Type: {0}", teInfo.Exception.GetType().Name))
                .AppendLine()
                .AppendLine("Exception Message:")
                .AppendLine(teInfo.Exception.Message)
                .AppendLine()
                .AppendLine("Exception Stack Trace:")
                .AppendLine(teInfo.Exception.StackTrace)
            End With
            MessageBox.Show(sb.ToString(), "Code Execution Measurer", MessageBoxButtons.OK, MessageBoxIcon.Error)

    End Select

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_ProfillingUtil">ProfillingUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />