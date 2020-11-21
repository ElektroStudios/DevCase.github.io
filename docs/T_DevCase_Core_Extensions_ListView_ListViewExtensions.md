# ListViewExtensions Class
 

Contains custom extension methods to use with ListView control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.ListView.ListViewExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class ListViewExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class ListViewExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As ListViewExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class ListViewExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type ListViewExtensions =  class end
```

The ListViewExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Copy">Copy(ListView)</a></td><td>
Copies all the text contained in the items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Copy_1">Copy(ListView, Int32)</a></td><td>
Copies all the text contained in the items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Copy_2">Copy(ListView, String)</a></td><td>
Copies all the text contained in the items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Copy_3">Copy(ListView, String, Int32)</a></td><td>
Copies all the text contained in the items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyCheckedItems">CopyCheckedItems(ListView)</a></td><td>
Copies all the text contained in the current checked items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyCheckedItems_1">CopyCheckedItems(ListView, String)</a></td><td>
Copies all the text contained in the current checked items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyCheckedItems_2">CopyCheckedItems(ListView, String, Int32)</a></td><td>
Copies all the text contained in the current checked items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItem">CopyItem(ListView, Int32)</a></td><td>
Copies all the text contained in the specified ListViewItem to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItem_1">CopyItem(ListView, Int32, String)</a></td><td>
Copies all the text contained in the specified ListViewItem to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItem_2">CopyItem(ListView, Int32, String, Int32)</a></td><td>
Copies all the text contained in the specified ListViewItem to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItems">CopyItems(ListView, Int32[])</a></td><td>
Copies all the text contained in the specified items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItems_1">CopyItems(ListView, Int32[], String)</a></td><td>
Copies all the text contained in the specified items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItems_2">CopyItems(ListView, Int32[], String, Int32)</a></td><td>
Copies all the text contained in the specified items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopySelectedItems">CopySelectedItems(ListView)</a></td><td>
Copies all the text contained in the current selected items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopySelectedItems_1">CopySelectedItems(ListView, String)</a></td><td>
Copies all the text contained in the current selected items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_CopySelectedItems_2">CopySelectedItems(ListView, String, Int32)</a></td><td>
Copies all the text contained in the current selected items of ListView to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Deserialize">Deserialize</a></td><td>
Deserializes the items of the ListView from a binary local file. 

 You can use this method to restore the contents of a ListView that were saved using the <a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Serialize">Serialize(ListView, String)</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_ExportToCSV">ExportToCSV</a></td><td>
Exports the source ListView to `CSV` table format.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_ExportToXml">ExportToXml</a></td><td>
Exports the source ListView to `Xml` format.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_MoveSelectedItems">MoveSelectedItems(ListView, RowMoveDirection)</a></td><td>
Moves up or down the selected items of the ListView.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_MoveSelectedItems_1">MoveSelectedItems(ListView, RowMoveDirection, IEnumerable(Int32))</a></td><td>
Moves up or down the selected items of the ListView.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_RemoveDuplicatedItems">RemoveDuplicatedItems</a></td><td>
Removes duplicated items in the ListView. 

 Comparison is done by comparing the text of the index of the specified subitems.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_RemoveSelectedItems">RemoveSelectedItems</a></td><td>
Removes the selected items from ListView.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Serialize">Serialize</a></td><td>
Serializes the items of the ListView to a binary local file. 

 You can use this method to backup the contents of a ListView, then restore them with the <a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Deserialize">Deserialize(ListView, String)</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_SetColumnIndices">SetColumnIndices(ListView, Int32)</a></td><td>
Indices the rows of a column of the ListView.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_SetColumnIndices_1">SetColumnIndices(ListView, Int32, Int32)</a></td><td>
Indices the rows of a column of the ListView.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_ToDataGridView">ToDataGridView</a></td><td>
Converts the source ListView to a DataGridView.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_ToDataTable">ToDataTable</a></td><td>
Converts the source ListView to a DataTable.</td></tr></table>&nbsp;
<a href="#listviewextensions-class">Back to Top</a>

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
<a href="#listviewextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView Namespace</a><br />