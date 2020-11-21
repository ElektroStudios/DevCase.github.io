# MP3ValWrapper Class
 

A wrapper of `MP3Val.exe` application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.MP3Val.MP3ValWrapper<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class MP3ValWrapper : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class MP3ValWrapper
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3ValWrapper
```

**C++**<br />
``` C++
public ref class MP3ValWrapper sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MP3ValWrapper =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The MP3ValWrapper type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MP3Val_MP3ValWrapper__ctor">MP3ValWrapper</a></td><td>
Initializes a new instance of the MP3ValWrapper class.</td></tr></table>&nbsp;
<a href="#mp3valwrapper-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Exists">Exists</a></td><td>
Gets a value indicating whether the `MP3Val.exe` file Exists.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_MP3ValWrapper_FilePath">FilePath</a></td><td>
Gets the `MP3Val.exe` filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Process">Process</a></td><td>
Gets the `MP3Val.exe`<a href="P_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Process">Process</a> instance.</td></tr></table>&nbsp;
<a href="#mp3valwrapper-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Analyze">Analyze(FileInfo)</a></td><td>
Analyzes a file for errors.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Analyze_1">Analyze(String)</a></td><td>
Analyzes a file for errors.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Fix">Fix(FileInfo, Boolean, Boolean)</a></td><td>
Tries to fix problems in the specified audio file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Fix_1">Fix(String, Boolean, Boolean)</a></td><td>
Tries to fix problems in the specified audio file.</td></tr></table>&nbsp;
<a href="#mp3valwrapper-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Exited">Exited</a></td><td>
Event raised when the `MP3Val.exe` process has exited.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Started">Started</a></td><td>
Event raised when the `MP3Val.exe` process has been started.</td></tr></table>&nbsp;
<a href="#mp3valwrapper-class">Back to Top</a>

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
<a href="#mp3valwrapper-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Friend WithEvents MP3Val As New MP3ValWrapper("C:\Program Files (x86)\MP3 Val\mp3val.exe")

    Private Sub Test() Handles MyBase.Shown

        ' Analyzes an MP3 file.
        MP3Val.Analyze("C:\File.mp3")

        ' Fix an MP3 file.
        MP3Val.Fix("C:\File.mp3")

    End Sub

    Private Sub MP3Val_Started(ByVal sender As Object, ByVal e As MP3ValStartedEventArgs) _
    Handles MP3Val.Started

        Dim sb As New System.Text.StringBuilder
        With sb
            .AppendLine(String.Format("Starting a ""{0}"" task", e.Task.ToString()))
            .AppendLine(String.Format("Input file is: ""{0}""", e.File))
            .AppendLine(String.Format("mp3val.exe process id (PID) is: {0}", CStr(DirectCast(sender, MP3ValWrapper).Process.Id)))
        End With

        Debug.WriteLine(String.Format("Start Time: {0}", Date.Now.ToLongTimeString))
        Debug.WriteLine(sb.ToString())

    End Sub

    Private Sub MP3Val_Exited(ByVal sender As Object, ByVal e As MP3ValExitedEventArgs) _
    Handles MP3Val.Exited

        Dim sb As New System.Text.StringBuilder

        sb.AppendLine(String.Format("Finished a ""{1}"" task in file ""{2}""{0}",
                                    Environment.NewLine,
                                    e.Task.ToString(),
                                    e.File))

        sb.AppendLine(String.Format("File information:{0}{1}{0}",
                                    Environment.NewLine,
                                    e.InfoMessage))

        sb.AppendLine("Warnings found:")
        If e.Warnings.Count <> 0 Then
            For Each wrn As String In e.Warnings
                sb.AppendLine(wrn)
            Next wrn
        Else
            sb.AppendLine("Any" & Environment.NewLine)
        End If

        sb.AppendLine("Errors found:")
        If e.Errors.Count <> 0 Then
            For Each err As String In e.Errors
                sb.AppendLine(err)
            Next err
        Else
            sb.AppendLine("Any" & Environment.NewLine)
        End If

        sb.AppendLine(String.Format("File need fix?: {0}",
                                    CStr(e.FileNeedFix)))

        If e.Task = MP3ValTask.Fix Then
            sb.AppendLine(String.Format("File was fixed?: {0}",
                                         CStr(e.FileIsFixed)))
        End If

        Debug.WriteLine(sb.ToString())
        Debug.WriteLine(String.Format("End Time: {0}", Date.Now.ToLongTimeString))

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val Namespace</a><br />