# DebuggerNotify Class
 

Provides a mechanism to notify when a debugger in user-mode is attached to or detached from the current process.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Diagnostics.DebuggerNotify<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class DebuggerNotify : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class DebuggerNotify
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As DebuggerNotify
```

**C++**<br />
``` C++
public ref class DebuggerNotify : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type DebuggerNotify =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The DebuggerNotify type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_DebuggerNotify__ctor">DebuggerNotify</a></td><td>
Initializes a new instance of the DebuggerNotify class.</td></tr></table>&nbsp;
<a href="#debuggernotify-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_DebuggerNotify_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#debuggernotify-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Diagnostics_DebuggerNotify_StatusChanged">StatusChanged</a></td><td>
Occurs when a debugger is attached to or detached from the current process.</td></tr></table>&nbsp;
<a href="#debuggernotify-class">Back to Top</a>

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
<a href="#debuggernotify-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1

    Private WithEvents DebuggerNotify As DebuggerNotify

    Public Sub New()
        MyClass.InitializeComponent()
        Me.DebuggerNotify = New DebuggerNotify()
    End Sub

    Private Sub DebuggerNotify_StatusChanged(ByVal sender As Object, ByVal e As DebuggerNotifyEventArgs) Handles DebuggerNotify.StatusChanged
        Dim msg As String = $"Debugger status changed to {NameOf(e.IsAttached)}: {e.IsAttached}"
        Console.WriteLine(msg)
    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />