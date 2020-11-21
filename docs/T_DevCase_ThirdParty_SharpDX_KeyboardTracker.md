# KeyboardTracker Class
 

Track and notify the keyboard events.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.SharpDX.KeyboardTracker<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class KeyboardTracker : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class KeyboardTracker
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardTracker
```

**C++**<br />
``` C++
public ref class KeyboardTracker sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type KeyboardTracker =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The KeyboardTracker type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SharpDX_KeyboardTracker__ctor">KeyboardTracker</a></td><td>
Initializes a new instance of the KeyboardTracker class.</td></tr></table>&nbsp;
<a href="#keyboardtracker-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SharpDX_KeyboardTracker_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#keyboardtracker-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_SharpDX_KeyboardTracker_KeyboardInput">KeyboardInput</a></td><td>
Occurs when they keyboard sends input.</td></tr></table>&nbsp;
<a href="#keyboardtracker-class">Back to Top</a>

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
<a href="#keyboardtracker-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Friend WithEvents KeyboardTracker As KeyboardTracker

Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Load

    Me.KeyboardTracker = New KeyboardTracker()

End Sub

Private Sub KeyboardTracker_KeyboardInput(ByVal sender As Object, ByVal e As KeyboardInputEventArgs) _
Handles KeyboardTracker.KeyboardInput

    Me.Label1.Text = e.Key.ToString()
    Me.Label2.Text = e.State.ToString()

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX Namespace</a><br />