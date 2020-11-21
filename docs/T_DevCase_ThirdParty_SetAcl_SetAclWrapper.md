# SetAclWrapper Class
 

A wrapper of `SetACL.exe` application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.SetAcl.SetAclWrapper<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class SetAclWrapper : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class SetAclWrapper
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As SetAclWrapper
```

**C++**<br />
``` C++
public ref class SetAclWrapper sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SetAclWrapper =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The SetAclWrapper type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SetAcl_SetAclWrapper__ctor">SetAclWrapper</a></td><td>
Initializes a new instance of the SetAclWrapper class.</td></tr></table>&nbsp;
<a href="#setaclwrapper-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SetAcl_SetAclWrapper_Exists">Exists</a></td><td>
Gets a value indicating whether the `SetACL.exe` file Exists.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SetAcl_SetAclWrapper_FilePath">FilePath</a></td><td>
Gets the `SetACL.exe` filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SetAcl_SetAclWrapper_LogFilePath">LogFilePath</a></td><td>
Gets the `SetACL.exe` log filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SetAcl_SetAclWrapper_Process">Process</a></td><td>
Gets the `SetACL.exe`<a href="P_DevCase_ThirdParty_SetAcl_SetAclWrapper_Process">Process</a> instance.</td></tr></table>&nbsp;
<a href="#setaclwrapper-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SetAcl_SetAclWrapper_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SetAcl_SetAclWrapper_SetOwnership">SetOwnership</a></td><td>
Takes ownership of a registry key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SetAcl_SetAclWrapper_SetPermission">SetPermission</a></td><td>
Takes ownership of a registry key.</td></tr></table>&nbsp;
<a href="#setaclwrapper-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_SetAcl_SetAclWrapper_Exited">Exited</a></td><td>
Event raised when the `SetACL.exe` process has exited.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_SetAcl_SetAclWrapper_Started">Started</a></td><td>
Event raised when the `SetACL.exe` process has been started.</td></tr></table>&nbsp;
<a href="#setaclwrapper-class">Back to Top</a>

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
<a href="#setaclwrapper-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Friend WithEvents Wrapper As New SetAclWrapper(".\SetACL.exe")

Private Sub Test() Handles Button1.Click

    Wrapper.SetOwnership("HKCU\Test", True)
    Wrapper.SetPermission("HKCU\Test", True, SetAclPermission.Full)

End Sub

Private Sub Wrapper_Started(ByVal sender As Object, ByVal e As SetAclStartedEventArgs) _
Handles Wrapper.Started

    ProgressBar1.Value = ProgressBar1.Minimum

    Dim sb As New System.Text.StringBuilder
    With sb
        .AppendLine(String.Format("Arguments: ""{0}""", e.Arguments))
        .AppendLine(String.Format("SetACL.exe process id (PID) is: {0}", CStr(DirectCast(sender, SetAclWrapper).Process.Id)))
    End With

    Debug.WriteLine(String.Format("Start Time: {0}", Date.Now.ToLongTimeString))
    Debug.WriteLine(sb.ToString())

End Sub

Private Sub Wrapper_Exited(ByVal sender As Object, ByVal e As SetAclExitedEventArgs) _
Handles Wrapper.Exited

    Dim sb As New Global.System.Text.StringBuilder
    With sb
        ' .AppendLine(String.Format("Arguments: ""{0}""", e.Arguments))
        .AppendLine(String.Format("Exit Code: ""{0}""", e.ExitCode))
    End With

    If Not String.IsNullOrEmpty(e.ErrorMessage) Then
        sb.AppendLine(String.Format("Error Information: {0}", e.ErrorMessage))
        Process.Start(Wrapper.LogFilePath)
    End If

    Debug.WriteLine(sb.ToString())
    Debug.WriteLine(String.Format("End Time: {0}", Date.Now.ToLongTimeString))

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl Namespace</a><br />