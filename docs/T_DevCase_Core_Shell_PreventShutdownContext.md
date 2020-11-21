# PreventShutdownContext Class
 

Provides a mechanism to prevent any system shutdown/restart/log-off request during the life-cycle of a instance of this class. 

 Applications should use this class as they begin an operation that cannot be interrupted, such as burning a CD or DVD. 

 This class is to be used in either a `Using` statement or for the life-cycle of the current application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.PreventShutdownContext<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class PreventShutdownContext : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class PreventShutdownContext
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As PreventShutdownContext
```

**C++**<br />
``` C++
public ref class PreventShutdownContext sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PreventShutdownContext =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The PreventShutdownContext type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Shell_PreventShutdownContext__ctor">PreventShutdownContext</a></td><td>
Initializes a new instance of the PreventShutdownContext class.</td></tr></table>&nbsp;
<a href="#preventshutdowncontext-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_PreventShutdownContext_Reason">Reason</a></td><td>
Gets or sets the reason for which the current application must prevent system shutdown. 

 Because users are typically in a hurry when shutting down the system, they may spend only a few seconds looking at the shutdown reasons that are displayed by the system. Therefore, it is important that your reason strings are short and clear.</td></tr></table>&nbsp;
<a href="#preventshutdowncontext-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Shell_PreventShutdownContext_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#preventshutdowncontext-class">Back to Top</a>

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
<a href="#preventshutdowncontext-class">Back to Top</a>

## Remarks
Original source-code: <a href="https://github.com/dahall/Vanara/blob/master/WIndows.Forms/Contexts/PreventShutdownContext.cs" target="_blank">https://github.com/dahall/Vanara/blob/master/WIndows.Forms/Contexts/PreventShutdownContext.cs</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using psc As New PreventShutdownContext("Critical operation is in progress...")
    ' Do something that can't be interrupted... 
End Using
```


## Examples
This is a code example. 
**VB**<br />
``` VB
Public NotInheritable Class Form1 : Inherits Form

    Private psc As PreventShutdownContext

    Private Sub AllowShutdown()
        If (Me.psc IsNot Nothing) Then
            Me.psc.Dispose()
            Me.psc = Nothing
        End If
    End Sub

    Private Sub DisallowShutdown()
        If (Me.psc Is Nothing) Then
            Me.psc = New PreventShutdownContext("Application defined reason goes here.")
        End If
    End Sub

    Protected Overrides Sub OnShown(ByVal e As EventArgs)
        Me.DisallowShutdown()
        MyBase.OnShown(e)
    End Sub

End Class
```


## Examples
This is a code example using the `using` statement. 
**C#**<br />
``` C#
using (new PreventShutdownContext("Critical operation is in progress...")) {
   // Do something that can't be interrupted...
}
```


## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />