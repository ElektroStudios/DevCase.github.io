# FormDragger Class
 

Adds dragging capabilities to a single or multiple Form when clicking on they client area.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.FormDragger<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class FormDragger : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class FormDragger
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormDragger
```

**C++**<br />
``` C++
public ref class FormDragger sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type FormDragger =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The FormDragger type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger__ctor">FormDragger()</a></td><td>
Initializes a new instance of the FormDragger class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger__ctor_1">FormDragger(IEnumerable(Form))</a></td><td>
Initializes a new instance of the FormDragger class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger__ctor_2">FormDragger(Form, Boolean, Cursor)</a></td><td>
Initializes a new instance of the FormDragger class.</td></tr></table>&nbsp;
<a href="#formdragger-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Application_UserInterface_FormDragger_Empty">Empty</a></td><td>
Represents a nul FormDragger instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_FormDragger_Forms">Forms</a></td><td>
Gets an IEnumerable(T) collection that contains the owner Forms that can perform draggable operations.</td></tr></table>&nbsp;
<a href="#formdragger-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_AddControl">AddControl</a></td><td>
Assigns the specified Control as a draggable element.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_AddControls">AddControls</a></td><td>
Assigns the specified controls as draggable elements of they parents Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_AddForm">AddForm</a></td><td>
Assigns the specified Form as a draggable element.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_FindFormDragInfo_1">FindFormDragInfo(Control)</a></td><td>
Finds the <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_FindFormDragInfo_2">FindFormDragInfo(Form)</a></td><td>
Finds the <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_FindFormDragInfo">FindFormDragInfo(String, StringComparison)</a></td><td>
Finds the <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_RemoveControl">RemoveControl</a></td><td>
Removes the specified Control from the draggable elements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_RemoveControls">RemoveControls</a></td><td>
Removes the specified controls from the draggable elements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_FormDragger_RemoveForm">RemoveForm</a></td><td>
Removes the specified Form from the draggable elements.</td></tr></table>&nbsp;
<a href="#formdragger-class">Back to Top</a>

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
<a href="#formdragger-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    ''' <summary>
    ''' The <see cref="FormDragger"/> instance that manages the form(s) dragging.
    ''' </summary>
    Friend FormDrag As FormDragger = FormDragger.Empty

    Private Sub Test() Handles MyBase.Shown
        Me.InitializeDrag()
    End Sub

    Private Sub InitializeDrag()

        ' 1st way, using the single-Form constructor:
        Me.FormDrag = New FormDragger(Me, enabled:=True, cursor:=Cursors.SizeAll)

        ' 2nd way, using the multiple-Forms constructor:
        ' Me.FormDrag = New FormDragger({Me, Form2, form3})

        ' 3rd way, using the default constructor then adding a Form into the collection:
        ' Me.FormDrag = New FormDragger
        ' Me.FormDrag.AddForm(Me, enabled:=True, cursor:=Cursors.SizeAll)

    End Sub

    ''' <summary>
    ''' Alternates the dragging enabled of the specified form.
    ''' </summary>
    ''' <param name="form">The form.</param>
    Private Sub AlternateDragEnabled(ByVal form As Form)

        Dim formInfo As FormDragInfo = Me.FormDrag.FindFormDragInfo(form)
        formInfo.Enabled = Not formInfo.Enabled

    End Sub

    Private Sub Button1_Click(ByVal sender As Object, ByVal e As EventArgs) _
    Handles Button1.Click

        Me.AlternateDragEnabled(Me)

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />