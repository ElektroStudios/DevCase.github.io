# TestExecutionInfo Class
 

Defines the info of a code-execution test.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Diagnostics.TestExecutionInfo<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("TestExecutionInfo")]
public sealed class TestExecutionInfo : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("TestExecutionInfo")>
Public NotInheritable Class TestExecutionInfo
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As TestExecutionInfo
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"TestExecutionInfo")]
public ref class TestExecutionInfo sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("TestExecutionInfo")>]
type TestExecutionInfo =  
    class
        inherit AestheticObject
    end
```

The TestExecutionInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_TestExecutionInfo__ctor">TestExecutionInfo</a></td><td>
Initializes a new instance of the TestExecutionInfo class.</td></tr></table>&nbsp;
<a href="#testexecutioninfo-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Diagnostics_TestExecutionInfo_Elapsed">Elapsed</a></td><td>
Gets the elapsed execution time.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Diagnostics_TestExecutionInfo_Exception">Exception</a></td><td>
Gets the <a href="P_DevCase_Core_Diagnostics_TestExecutionInfo_Exception">Exception</a> that occured during method execution, if any.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Diagnostics_TestExecutionInfo_Method">Method</a></td><td>
Gets the method metadata.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Diagnostics_TestExecutionInfo_Success">Success</a></td><td>
Gets a value indicating whether the execution of the method was successful.</td></tr></table>&nbsp;
<a href="#testexecutioninfo-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#testexecutioninfo-class">Back to Top</a>

## Examples
This is a code example of a synchronous TestExecutionInfo. 
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

End Sub
```


## Examples
This is a code example of an asynchronous TestExecutionInfo. 
**VB**<br />
``` VB
Sub Test()

    Dim taskTestTime As Task(Of TestExecutionInfo) =
        TestTimeAsync(Sub()
                         For x As Integer = 0 To 5000
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
<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />