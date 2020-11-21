# EditControlHook Class
 

Registers a `WndProc` hook to listen and notify about edit-menu messages of an edit-control. ( Copy, Cut, Paste, Delete, Undo )


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.EditControlHook<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class EditControlHook : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class EditControlHook
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As EditControlHook
```

**C++**<br />
``` C++
public ref class EditControlHook sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type EditControlHook =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The EditControlHook type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_EditControlHook__ctor">EditControlHook</a></td><td>
Initializes a new instance of the EditControlHook class.</td></tr></table>&nbsp;
<a href="#editcontrolhook-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_EditControlHook_Controls">Controls</a></td><td>
Gets or sets the edit-controls that will notify for windows messages.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_EditControlHook_Enabled">Enabled</a></td><td>
Gets or sets a value indicating whether this EditControlHook is enabled.</td></tr></table>&nbsp;
<a href="#editcontrolhook-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_EditControlHook_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#editcontrolhook-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_EditControlHook_Copy">Copy</a></td><td>
Occurs when the text of the control is copied.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_EditControlHook_Cut">Cut</a></td><td>
Occurs when the text of the control is cutted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_EditControlHook_Delete">Delete</a></td><td>
Occurs when the text of the control is deleted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_EditControlHook_Paste">Paste</a></td><td>
Occurs when the text of the control is pasted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_EditControlHook_Undo">Undo</a></td><td>
Occurs when the text of the control is undone.</td></tr></table>&nbsp;
<a href="#editcontrolhook-class">Back to Top</a>

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
<a href="#editcontrolhook-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Friend WithEvents EditControlHook As New EditControlHook

Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Load

    ' Capture the Edit-Menu messages for TextBox1 and TextBox2
    Me.EditControlHook.Controls = {Me.TextBox1, Me.TextBox2}

    ' Enable the Hook
    Me.EditControlHook.Enabled = True

End Sub

Private Sub Form1_FormClosing() Handles MyBase.FormClosing

    Me.EditControlHook.Dispose()

End Sub

Private Sub EditControlHook_Copy(ByVal sender As Object, ByVal e As EventArgs) _
Handles EditControlHook.Copy

    MessageBox.Show(String.Format("Text copied in control: {0}", DirectCast(sender, Control).Name))

End Sub

Private Sub EditControlHook_Cut(ByVal sender As Object, ByVal e As EventArgs) _
Handles EditControlHook.Cut

    MessageBox.Show(String.Format("Text cutted in control: {0}", DirectCast(sender, Control).Name))

End Sub

Private Sub EditControlHook_Paste(ByVal sender As Object, ByVal e As EventArgs) _
Handles EditControlHook.Paste

    MessageBox.Show(String.Format("Text pasted in control: {0}", DirectCast(sender, Control).Name))

End Sub

Private Sub EditControlHook_Delete(ByVal sender As Object, ByVal e As EventArgs) _
Handles EditControlHook.Delete

    MessageBox.Show(String.Format("Text deleted in control: {0}", DirectCast(sender, Control).Name))

End Sub

Private Sub EditControlHook_Undo(ByVal sender As Object, ByVal e As EventArgs) _
Handles EditControlHook.Undo

    MessageBox.Show(String.Format("Text undone in control: {0}", DirectCast(sender, Control).Name))

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />