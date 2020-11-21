# DevListBox Class
 

A extended ListBox control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.Control<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.ListControl<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.ListBox<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevListBox<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(ListBox), "ListBox.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultBindingPropertyAttribute("SelectedValue")]
[DefaultPropertyAttribute("Items")]
[DefaultEventAttribute("SelectedIndexChanged")]
public class DevListBox : ListBox, IBufferedControl
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(ListBox), "ListBox.bmp")>
<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>
<ComVisibleAttribute(true)>
<DefaultBindingPropertyAttribute("SelectedValue")>
<DefaultPropertyAttribute("Items")>
<DefaultEventAttribute("SelectedIndexChanged")>
Public Class DevListBox
	Inherits ListBox
	Implements IBufferedControl
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListBox
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(ListBox), L"ListBox.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType::AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultBindingPropertyAttribute(L"SelectedValue")]
[DefaultPropertyAttribute(L"Items")]
[DefaultEventAttribute(L"SelectedIndexChanged")]
public ref class DevListBox : public ListBox, 
	IBufferedControl
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(ListBox), "ListBox.bmp")>]
[<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>]
[<ComVisibleAttribute(true)>]
[<DefaultBindingPropertyAttribute("SelectedValue")>]
[<DefaultPropertyAttribute("Items")>]
[<DefaultEventAttribute("SelectedIndexChanged")>]
type DevListBox =  
    class
        inherit ListBox
        interface IBufferedControl
    end
```

The DevListBox type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListBox__ctor">DevListBox</a></td><td>
Initializes a new instance of the DevListBox class.</td></tr></table>&nbsp;
<a href="#devlistbox-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListBox_DoubleBuffered">DoubleBuffered</a></td><td>
Gets or sets a value indicating whether this control should redraw its surface using a secondary buffer to reduce or prevent flicker.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListBox_ItemHeight">ItemHeight</a></td><td>
Gets or sets the height of an item in the control.
 (Overrides ListBox.ItemHeight.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListBox_PreventFlickering">PreventFlickering</a></td><td>
Gets or sets a value that indicates whether the control should avoid unwanted flickering effects. 

 If `true` (`True` in Visual Basic), this will avoid any flickering effect on the control, however, it will also have a negative impact by slowing down the responsiveness of the control about to 30% slower. 

 This negative impact doesn't affect to the performance of the application itself, just to the performance of this control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListBox_ReadOnly">ReadOnly</a></td><td>
Gets or sets a value indicating whether the control is in read-only mode.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListBox_StateDisabled">StateDisabled</a></td><td>
Gets the appearance layout for the control when it is disabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListBox_StateEnabled">StateEnabled</a></td><td>
Gets the appearance layout for the control when it is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListBox_StateReadOnly">StateReadOnly</a></td><td>
Gets the appearance layout for the control when it is in read-only mode.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListBox_TextFormat">TextFormat</a></td><td>
Gets the text formatting layout for the items in the control.</td></tr></table>&nbsp;
<a href="#devlistbox-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_CopyItem">CopyItem</a></td><td>
Copies the text of the specified item in the ListBox to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_CopyItems">CopyItems</a></td><td>
Copies the text of the specified items in the ListBox to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_CopySelectedItems">CopySelectedItems</a></td><td>
Copies the text of the current selected items in the ListBox to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_DeselectAllItems">DeselectAllItems</a></td><td>
Deselects all the items in ListBox.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_DeselectAllItemsNoJump">DeselectAllItemsNoJump</a></td><td>
Selects all the items in ListBox without scrolling to its item position.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Deserialize">Deserialize</a></td><td>
Deserializes the items of the ListBox from a binary local file. 

 You can use this method to restore the items of a ListBox that were saved using the <a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Serialize">Serialize(ListBox, String, SerializationFormat)</a> method.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ForEachControl">ForEachControl(Boolean, Action(Control))</a></td><td>Overloaded.  
Iterate through all the controls in the source Control and performs the specified action on each one.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ForEachControl__1">ForEachControl(T)(Boolean, Action(Control))</a></td><td>Overloaded.  
Iterate through all the controls of the specified type in the source Control and performs the specified action on each one.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_GetBoundsRelativeToForm">GetBoundsRelativeToForm</a></td><td>
Gets the bounds of the source Control relatively to its parent Form.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_GetControlStyle">GetControlStyle</a></td><td>
Gets the value of the specified ControlStyles bit for the source control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_GetEventHandlers">GetEventHandlers(String)</a></td><td>Overloaded.  
Gets all the delegates associated to the specified event raised by the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Component_ComponentExtensions_GetEventHandlers">GetEventHandlers(String)</a></td><td>Overloaded.  
Gets all the delegates associated to the specified event raised by the source Component.
 (Defined by <a href="T_DevCase_Core_Extensions_Component_ComponentExtensions">ComponentExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_InvokeWhenHandleValid">InvokeWhenHandleValid</a></td><td>
Performs an action on the specified Control after its handle has been created (that is, when HandleCreated event is fired). 

 If the handle has already been created, the action is executed immediately.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_IsInDesignMode">IsInDesignMode</a></td><td>
Determines whether the source Control is in design mode.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_IsInRuntimeMode">IsInRuntimeMode</a></td><td>
Determines whether the source Control is in runtime mode.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_MoveSelectedItems">MoveSelectedItems</a></td><td>
Moves up or down the selected items of the ListBox.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveDuplicates">RemoveDuplicates()</a></td><td>Overloaded.  
Removes duplicated items in the source ListBox, using the default EqualityComparer(T) to compare the items.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveDuplicates__1">RemoveDuplicates(T)()</a></td><td>Overloaded.  
Removes duplicated items of the specified Type in the source ListBox, using the default EqualityComparer(T) to compare the items.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveDuplicates__1_1">RemoveDuplicates(T)(IEqualityComparer(T))</a></td><td>Overloaded.  
Removes duplicated items of the specified Type in the source ListBox.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveEmptyOrWhiteSpaceStrings">RemoveEmptyOrWhiteSpaceStrings</a></td><td>
Removes any empty string items (String) and also string items that consists only of white-space characters in the source ListBox.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveEmptyStrings">RemoveEmptyStrings</a></td><td>
Removes any empty string items (String) in the source ListBox.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveItems__1">RemoveItems(T)</a></td><td>
Removes items of the specified Type in the source ListBox given a condition.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveSelectedItems">RemoveSelectedItems</a></td><td>
Removes the selected items from ListBox.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ResumeDrawing">ResumeDrawing()</a></td><td>Overloaded.  
Allow the source Control to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ResumeDrawing_1">ResumeDrawing(Boolean)</a></td><td>Overloaded.  
Allow the source Control to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SelectAllItems">SelectAllItems</a></td><td>
Selects all the items in ListBox.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SelectAllItemsNoJump">SelectAllItemsNoJump</a></td><td>
Selects all the items in ListBox without scrolling to its item position.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendKey_1">SendKey(Keys, KeyBehavior)</a></td><td>Overloaded.  
Sends a keystroke to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendKey">SendKey(VirtualKeys, KeyBehavior)</a></td><td>Overloaded.  
Sends a keystroke to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendMouseButton">SendMouseButton(MouseButton)</a></td><td>Overloaded.  
Sends a mouse button click to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendMouseButton_1">SendMouseButton(MouseButton, Point)</a></td><td>Overloaded.  
Sends a mouse button click to the specified coordinates on the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Serialize">Serialize</a></td><td>
Serializes the items of the ListBox to a binary local file. 

 You can use this method to backup the items of a ListBox, then restore them with the <a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Deserialize">Deserialize(ListBox, String, SerializationFormat)</a> method.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetControlStyle">SetControlStyle</a></td><td>
Sets a specified ControlStyles flag to either `true` (`True` in Visual Basic) or `false` (`False` in Visual Basic) for the source control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetDoubleBuffer">SetDoubleBuffer</a></td><td>
Sets the value of DoubleBuffered property for the source Control. 

 You should call this method to set double buffer for a control, instead of calling <a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetControlStyle">SetControlStyle(Control, ControlStyles, Boolean)</a> method with OptimizedDoubleBuffer flag.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SetSelectedNoJump">SetSelectedNoJump(Int32, ListBoxItemSelectionState)</a></td><td>Overloaded.  
Selects or unselects the specified item in ListBox without scrolling to its item position.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SetSelectedNoJump_1">SetSelectedNoJump(Int32[], ListBoxItemSelectionState)</a></td><td>Overloaded.  
Selects or unselects the specified items in ListBox without scrolling to their item positions.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SetSelectedNoJump_2">SetSelectedNoJump(String, ListBoxItemSelectionState)</a></td><td>Overloaded.  
Selects or unselects the specified item in ListBox without scrolling to its item position.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SetSelectedNoJump_3">SetSelectedNoJump(String[], ListBoxItemSelectionState)</a></td><td>Overloaded.  
Selects or unselects the specified items in ListBox without scrolling to their item positions.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetVisualStyle">SetVisualStyle</a></td><td>
Changes the color appearance of the source Control using the specified style.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Sort__1">Sort(T)()</a></td><td>Overloaded.  
Sorts the items in the ListBox.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Sort__1_1">Sort(T)(IComparer(T))</a></td><td>Overloaded.  
Sorts the items in the ListBox.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SuspendDrawing">SuspendDrawing</a></td><td>
Prevents the source Control from being redrawn. 

 By calling this method, it will disallow painting events from firing on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_TransferAllItems">TransferAllItems</a></td><td>
Transfers all the items from the source ListBox to another.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_TransferSelectedItems">TransferSelectedItems</a></td><td>
Transfers the selected items from the source ListBox to another.
 (Defined by <a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions</a>.)</td></tr></table>&nbsp;
<a href="#devlistbox-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />