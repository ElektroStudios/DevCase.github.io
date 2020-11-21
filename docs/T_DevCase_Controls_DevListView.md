# DevListView Class
 

A extended ListView control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.Control<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.ListView<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevListView<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(ListView), "ListView.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultPropertyAttribute("Items")]
[DefaultEventAttribute("SelectedIndexChanged")]
[DockingAttribute(DockingBehavior.Ask)]
public class DevListView : ListView, 
	IBufferedControl
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(ListView), "ListView.bmp")>
<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>
<ComVisibleAttribute(true)>
<DefaultPropertyAttribute("Items")>
<DefaultEventAttribute("SelectedIndexChanged")>
<DockingAttribute(DockingBehavior.Ask)>
Public Class DevListView
	Inherits ListView
	Implements IBufferedControl
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListView
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(ListView), L"ListView.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType::AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultPropertyAttribute(L"Items")]
[DefaultEventAttribute(L"SelectedIndexChanged")]
[DockingAttribute(DockingBehavior::Ask)]
public ref class DevListView : public ListView, 
	IBufferedControl
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(ListView), "ListView.bmp")>]
[<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>]
[<ComVisibleAttribute(true)>]
[<DefaultPropertyAttribute("Items")>]
[<DefaultEventAttribute("SelectedIndexChanged")>]
[<DockingAttribute(DockingBehavior.Ask)>]
type DevListView =  
    class
        inherit ListView
        interface IBufferedControl
    end
```

The DevListView type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListView__ctor">DevListView</a></td><td>
Initializes a new instance of the DevListView class.</td></tr></table>&nbsp;
<a href="#devlistview-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_ColumnHeaderBackcolor">ColumnHeaderBackcolor</a></td><td>
Gets or sets the BackColor of the column headers.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_ColumnHeaderForeColor">ColumnHeaderForeColor</a></td><td>
Gets or sets the ForeColor of the column headers.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_ColumnHeaderSeparatorColor">ColumnHeaderSeparatorColor</a></td><td>
Gets or sets the ForeColor of the column header separators.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_DoubleBuffered">DoubleBuffered</a></td><td>
Gets or sets a value indicating whether this control should redraw its surface using a secondary buffer to reduce or prevent flicker.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_GridLineColor">GridLineColor</a></td><td>
Gets or sets the grid lines color.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_GridLines">GridLines</a></td><td>
Gets or sets a value indicating whether the control should use grid lines.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_ItemHighlightColor">ItemHighlightColor</a></td><td>
Gets or sets the color to use to highlight an item when it is focused.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_ItemNotFocusedHighlighColor">ItemNotFocusedHighlighColor</a></td><td>
Gets or sets the color to use to highlight an item when it is not focused.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_Items">Items</a></td><td>
Gets a collection containing all items in the control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_PreventFlickering">PreventFlickering</a></td><td>
Gets or sets a value that indicates whether the control should avoid unwanted flickering effects. 

 If `true` (`True` in Visual Basic), this will avoid any flickering effect on the control, however, it will also have a negative impact by slowing down the responsiveness of the control about to 30% slower. 

 This negative impact doesn't affect to the performance of the application itself, just to the performance of this control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevListView_UseDefaultGridLines">UseDefaultGridLines</a></td><td>
Gets or sets a value indicating whether the control should draw default grid lines.</td></tr></table>&nbsp;
<a href="#devlistview-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListView_Me_DrawColumnHeader">Me_DrawColumnHeader</a></td><td>
Handles the DrawColumnHeader event of the Me control.</td></tr></table>&nbsp;
<a href="#devlistview-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Controls_DevListView_ItemAdded">ItemAdded</a></td><td>
Occurs when a new item is added into the items collection of the control.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Controls_DevListView_ItemRemoved">ItemRemoved</a></td><td>
Occurs when a item is removed from the items collection of the control.</td></tr></table>&nbsp;
<a href="#devlistview-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Copy">Copy()</a></td><td>Overloaded.  
Copies all the text contained in the items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Copy_1">Copy(Int32)</a></td><td>Overloaded.  
Copies all the text contained in the items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Copy_2">Copy(String)</a></td><td>Overloaded.  
Copies all the text contained in the items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Copy_3">Copy(String, Int32)</a></td><td>Overloaded.  
Copies all the text contained in the items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyCheckedItems">CopyCheckedItems()</a></td><td>Overloaded.  
Copies all the text contained in the current checked items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyCheckedItems_1">CopyCheckedItems(String)</a></td><td>Overloaded.  
Copies all the text contained in the current checked items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyCheckedItems_2">CopyCheckedItems(String, Int32)</a></td><td>Overloaded.  
Copies all the text contained in the current checked items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItem">CopyItem(Int32)</a></td><td>Overloaded.  
Copies all the text contained in the specified ListViewItem to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItem_1">CopyItem(Int32, String)</a></td><td>Overloaded.  
Copies all the text contained in the specified ListViewItem to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItem_2">CopyItem(Int32, String, Int32)</a></td><td>Overloaded.  
Copies all the text contained in the specified ListViewItem to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItems">CopyItems(Int32[])</a></td><td>Overloaded.  
Copies all the text contained in the specified items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItems_1">CopyItems(Int32[], String)</a></td><td>Overloaded.  
Copies all the text contained in the specified items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItems_2">CopyItems(Int32[], String, Int32)</a></td><td>Overloaded.  
Copies all the text contained in the specified items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopySelectedItems">CopySelectedItems()</a></td><td>Overloaded.  
Copies all the text contained in the current selected items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopySelectedItems_1">CopySelectedItems(String)</a></td><td>Overloaded.  
Copies all the text contained in the current selected items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopySelectedItems_2">CopySelectedItems(String, Int32)</a></td><td>Overloaded.  
Copies all the text contained in the current selected items of ListView to the clipboard.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Deserialize">Deserialize</a></td><td>
Deserializes the items of the ListView from a binary local file. 

 You can use this method to restore the contents of a ListView that were saved using the <a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Serialize">Serialize(ListView, String)</a> method.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_ExportToCSV">ExportToCSV</a></td><td>
Exports the source ListView to `CSV` table format.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_ExportToXml">ExportToXml</a></td><td>
Exports the source ListView to `Xml` format.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ForEachControl">ForEachControl(Boolean, Action(Control))</a></td><td>Overloaded.  
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
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_MoveSelectedItems">MoveSelectedItems(RowMoveDirection)</a></td><td>Overloaded.  
Moves up or down the selected items of the ListView.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_MoveSelectedItems_1">MoveSelectedItems(RowMoveDirection, IEnumerable(Int32))</a></td><td>Overloaded.  
Moves up or down the selected items of the ListView.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_RemoveDuplicatedItems">RemoveDuplicatedItems</a></td><td>
Removes duplicated items in the ListView. 

 Comparison is done by comparing the text of the index of the specified subitems.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_RemoveSelectedItems">RemoveSelectedItems</a></td><td>
Removes the selected items from ListView.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ResumeDrawing">ResumeDrawing()</a></td><td>Overloaded.  
Allow the source Control to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ResumeDrawing_1">ResumeDrawing(Boolean)</a></td><td>Overloaded.  
Allow the source Control to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendKey_1">SendKey(Keys, KeyBehavior)</a></td><td>Overloaded.  
Sends a keystroke to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendKey">SendKey(VirtualKeys, KeyBehavior)</a></td><td>Overloaded.  
Sends a keystroke to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendMouseButton">SendMouseButton(MouseButton)</a></td><td>Overloaded.  
Sends a mouse button click to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendMouseButton_1">SendMouseButton(MouseButton, Point)</a></td><td>Overloaded.  
Sends a mouse button click to the specified coordinates on the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Serialize">Serialize</a></td><td>
Serializes the items of the ListView to a binary local file. 

 You can use this method to backup the contents of a ListView, then restore them with the <a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Deserialize">Deserialize(ListView, String)</a> method.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_SetColumnIndices">SetColumnIndices(Int32)</a></td><td>Overloaded.  
Indices the rows of a column of the ListView.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_SetColumnIndices_1">SetColumnIndices(Int32, Int32)</a></td><td>Overloaded.  
Indices the rows of a column of the ListView.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetControlStyle">SetControlStyle</a></td><td>
Sets a specified ControlStyles flag to either `true` (`True` in Visual Basic) or `false` (`False` in Visual Basic) for the source control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetDoubleBuffer">SetDoubleBuffer</a></td><td>
Sets the value of DoubleBuffered property for the source Control. 

 You should call this method to set double buffer for a control, instead of calling <a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetControlStyle">SetControlStyle(Control, ControlStyles, Boolean)</a> method with OptimizedDoubleBuffer flag.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetVisualStyle">SetVisualStyle</a></td><td>
Changes the color appearance of the source Control using the specified style.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SuspendDrawing">SuspendDrawing</a></td><td>
Prevents the source Control from being redrawn. 

 By calling this method, it will disallow painting events from firing on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_ToDataGridView">ToDataGridView</a></td><td>
Converts the source ListView to a DataGridView.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_ToDataTable">ToDataTable</a></td><td>
Converts the source ListView to a DataTable.
 (Defined by <a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions</a>.)</td></tr></table>&nbsp;
<a href="#devlistview-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />