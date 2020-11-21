# ControlClickNotifier Class
 

Notifies a click, double-click, or triple-click event on the specified <a href="P_DevCase_Core_Application_UserInterface_ControlClickNotifier_Control">Control</a>.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.ControlClickNotifier<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class ControlClickNotifier : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class ControlClickNotifier
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlClickNotifier
```

**C++**<br />
``` C++
public ref class ControlClickNotifier : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type ControlClickNotifier =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The ControlClickNotifier type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ControlClickNotifier__ctor">ControlClickNotifier</a></td><td>
Initializes a new instance of the <a href="E_DevCase_Core_Application_UserInterface_ControlClickNotifier_TripleClick">TripleClick</a> class.</td></tr></table>&nbsp;
<a href="#controlclicknotifier-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlClickNotifier_Control">Control</a></td><td>
Gets the <a href="P_DevCase_Core_Application_UserInterface_ControlClickNotifier_Control">Control</a> that owns this instance.</td></tr></table>&nbsp;
<a href="#controlclicknotifier-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ControlClickNotifier_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#controlclicknotifier-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_ControlClickNotifier_Click">Click</a></td><td>
Occurs when a single click occurs in the owner <a href="P_DevCase_Core_Application_UserInterface_ControlClickNotifier_Control">Control</a>.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_ControlClickNotifier_DoubleClick">DoubleClick</a></td><td>
Occurs when a double-click occurs in the owner <a href="P_DevCase_Core_Application_UserInterface_ControlClickNotifier_Control">Control</a>.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_ControlClickNotifier_TripleClick">TripleClick</a></td><td>
Occurs when a triple-click occurs in the owner <a href="P_DevCase_Core_Application_UserInterface_ControlClickNotifier_Control">Control</a>.</td></tr></table>&nbsp;
<a href="#controlclicknotifier-class">Back to Top</a>

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
<a href="#controlclicknotifier-class">Back to Top</a>

## Examples
This is a code example that selects all the text on a TextBox when triple-click occurs. 
**VB**<br />
``` VB
Friend WithEvents ClickNotifier As ControlClickNotifier

Public Sub Test() Handles MyBase.Shown

    Me.ClickNotifier = New ControlClickNotifier(Me.TextBox1)

End Sub

Private Sub ClickNotifier_MouseClick(ByVal sender As Object, ByVal e As MouseEventArgs) _
Handles ClickNotifier.TripleClick

    If (e.Button = MouseButtons.Left) Then

        Dim tb As TextBox = DirectCast(sender, TextBox)
        tb.SelectAll()

    End If

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />