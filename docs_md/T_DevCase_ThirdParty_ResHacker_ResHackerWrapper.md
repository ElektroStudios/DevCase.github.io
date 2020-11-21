# ResHackerWrapper Class
 

A wrapper of `ResHacker.exe` application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.ResHacker.ResHackerWrapper<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ResHackerWrapper : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class ResHackerWrapper
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResHackerWrapper
```

**C++**<br />
``` C++
public ref class ResHackerWrapper sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ResHackerWrapper =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The ResHackerWrapper type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper__ctor">ResHackerWrapper</a></td><td>
Initializes a new instance of the ResHackerWrapper class.</td></tr></table>&nbsp;
<a href="#reshackerwrapper-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_ResHacker_ResHackerWrapper_Exists">Exists</a></td><td>
Gets a value indicating whether the `ResHacker.exe` file Exists.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_ResHacker_ResHackerWrapper_FilePath">FilePath</a></td><td>
Gets the `ResHacker.exe` filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_ResHacker_ResHackerWrapper_LogFilePath">LogFilePath</a></td><td>
Gets the `ResHacker.exe` log filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_ResHacker_ResHackerWrapper_Process">Process</a></td><td>
Gets the `ResHacker.exe`<a href="P_DevCase_ThirdParty_ResHacker_ResHackerWrapper_Process">Process</a> instance.</td></tr></table>&nbsp;
<a href="#reshackerwrapper-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_AddResource">AddResource</a></td><td>
Adds a resource into the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_ExtractAllResources">ExtractAllResources</a></td><td>
Extracts all the resources of the specified type from the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_ExtractMainIcon">ExtractMainIcon</a></td><td>
Extracts the main icon from the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_ExtractResource">ExtractResource</a></td><td>
Extracts a resource from the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_RemoveMainIcon">RemoveMainIcon</a></td><td>
Deletes the main icon of the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_RemoveResource">RemoveResource</a></td><td>
Removes a resource in the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_ReplaceMainIcon">ReplaceMainIcon</a></td><td>
Replaces the main icon of the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_ReplaceResource">ReplaceResource</a></td><td>
Replaces a resource in the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_ResHacker_ResHackerWrapper_RunScript">RunScript</a></td><td>
Runs a ResHacker script.</td></tr></table>&nbsp;
<a href="#reshackerwrapper-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_ResHacker_ResHackerWrapper_Exited">Exited</a></td><td>
Event raised when the `ResHacker.exe` process has exited.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_ResHacker_ResHackerWrapper_Started">Started</a></td><td>
Event raised when the `ResHacker.exe` process has been started.</td></tr></table>&nbsp;
<a href="#reshackerwrapper-class">Back to Top</a>

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
<a href="#reshackerwrapper-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public NotInheritable Class Form1 : Inherits Form

    Friend WithEvents ResHacker As New ResHackerWrapper(".\ResHacker.exe")

    Private Sub Test() Handles Button1.Click

        Dim exitcode As Integer = ResHacker.ExtractMainIcon("C:\File.exe", "C:\Icon.ico")

    End Sub

    Private Sub ResHacker_Started(ByVal sender As Object, ByVal e As ResHackerStartedEventArgs) _
    Handles ResHacker.Started

        ProgressBar1.Value = ProgressBar1.Minimum

        Dim sb As New Global.System.Text.StringBuilder
        With sb
            .AppendLine(String.Format("Arguments: ""{0}""", e.Arguments))
            .AppendLine(String.Format("ResHacker.exe process id (PID) is: {0}", CStr(DirectCast(sender, ResHackerWrapper).Process.Id)))
        End With

        Debug.WriteLine(String.Format("Start Time: {0}", Date.Now.ToLongTimeString))
        Debug.WriteLine(sb.ToString())

    End Sub

    Private Sub ResHacker_Exited(ByVal sender As Object, ByVal e As ResHackerExitedEventArgs) _
    Handles ResHacker.Exited

        Dim sb As New Global.System.Text.StringBuilder
        With sb
            ' .AppendLine(String.Format("Arguments: ""{0}""", e.Arguments))
            .AppendLine(String.Format("Error Message: ""{0}""", e.ErrorMessage))
            .AppendLine(String.Format("Exit Code: ""{0}""", e.ExitCode))
        End With

        Debug.WriteLine(sb.ToString())
        Debug.WriteLine(String.Format("End Time: {0}", Date.Now.ToLongTimeString))

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker Namespace</a><br />