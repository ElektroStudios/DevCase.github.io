# UndoRedoMaskedTextBox Class
 

Undo/Redo mechanism for a MaskedTextBox.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Application_UserInterface_UndoRedo_1">DevCase.Core.Application.UserInterface.UndoRedo</a>(MaskedTextBox)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.UndoRedoMaskedTextBox<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class UndoRedoMaskedTextBox : UndoRedo<MaskedTextBox>
```

**VB**<br />
``` VB
Public NotInheritable Class UndoRedoMaskedTextBox
	Inherits UndoRedo(Of MaskedTextBox)
```

**VB Usage**<br />
``` VB Usage
Dim instance As UndoRedoMaskedTextBox
```

**C++**<br />
``` C++
public ref class UndoRedoMaskedTextBox sealed : public UndoRedo<MaskedTextBox^>
```

**F#**<br />
``` F#
[<SealedAttribute>]
type UndoRedoMaskedTextBox =  
    class
        inherit UndoRedo<MaskedTextBox>
    end
```

The UndoRedoMaskedTextBox type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_UndoRedoMaskedTextBox__ctor">UndoRedoMaskedTextBox</a></td><td>
Initializes a new instance of the UndoRedoMaskedTextBox class.</td></tr></table>&nbsp;
<a href="#undoredomaskedtextbox-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_UndoRedoMaskedTextBox_Events">Events</a></td><td>
Gets or sets the events being monitored for undo/redo operations.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_UndoRedoMaskedTextBox_TextUpdateBehavior">TextUpdateBehavior</a></td><td>
Gets or sets the update behavior of when to save the text to undo or redo.</td></tr></table>&nbsp;
<a href="#undoredomaskedtextbox-class">Back to Top</a>

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
<a href="#undoredomaskedtextbox-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public NotInheritable Class Form1 : Inherits Form

    Private undoRedo As UndoRedoMaskedTextBox

    Private Sub Form1_Load(ByVal sender As Object, ByVal e As EventArgs) _
    Handles MyBase.Load

        Me.undoRedo = New UndoRedoMaskedTextBox(Me.MaskedTextBox1) With {
            .Events = (UndoRedoMaskedTextBoxEvents.TextChanged Or UndoRedoMaskedTextBoxEvents.FontChanged),
            .TextUpdateBehavior = UndoRedoTextUpdateBehavior.OnLeave
        }

    End Sub

    Private Sub Button1_Click(sender As Object, e As EventArgs) _
    Handles Button1.Click

        Me.undoRedo.Undo()

    End Sub

    Private Sub Button2_Click(sender As Object, e As EventArgs) _
    Handles Button2.Click

        Me.undoRedo.Redo()

    End Sub

    Private Sub Form1_FormClosing(sender As Object, e As FormClosingEventArgs) _
    Handles MyBase.FormClosing

        Me.undoRedo.Dispose()

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />