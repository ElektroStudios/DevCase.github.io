# ProfillingUtil.TestTime Method 
 

Tests the execution of a Action and measures the elapsed time.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TestExecutionInfo TestTime(
	Action action
)
```

**VB**<br />
``` VB
Public Shared Function TestTime ( 
	action As Action
) As TestExecutionInfo
```

**VB Usage**<br />
``` VB Usage
Dim action As Action
Dim returnValue As TestExecutionInfo

returnValue = ProfillingUtil.TestTime(action)
```

**C++**<br />
``` C++
public:
static TestExecutionInfo^ TestTime(
	Action^ action
)
```

**F#**<br />
``` F#
static member TestTime : 
        action : Action -> TestExecutionInfo 

```


#### Parameters
&nbsp;<dl><dt>action</dt><dd>Type: System.Action<br />The Action to invoke.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Diagnostics_TestExecutionInfo">TestExecutionInfo</a><br />A <a href="T_DevCase_Core_Diagnostics_TestExecutionInfo">TestExecutionInfo</a> instance that contains the test info.

## Examples
This is a code example. 
**VB**<br />
``` VB
Sub Test()

    Dim successful As Boolean =
        TestSuccess(Sub() Convert.ToInt32("Hello World!"))

    Dim teInfo As TestExecutionInfo =
        TestTime(Sub()
                                    For x As Integer = 0 To 2500
                                        Console.WriteLine(x)
                                    Next x
                                End Sub)

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
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_ProfillingUtil">ProfillingUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />