# ListBoxExtensions Class
 

Contains custom extension methods to use with ListBox control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.ListBox.ListBoxExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class ListBoxExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class ListBoxExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As ListBoxExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class ListBoxExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type ListBoxExtensions =  class end
```

The ListBoxExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_AsIEnumerable">AsIEnumerable(ListBox.ObjectCollection)</a></td><td>
Converts the specified a ListBox.ObjectCollection to a IEnumerable(T).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_AsIEnumerable_1">AsIEnumerable(ListBox.SelectedObjectCollection)</a></td><td>
Converts the specified a ListBox.SelectedObjectCollection to a IEnumerable(T).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_AsIEnumerable__1">AsIEnumerable(T)(ListBox.ObjectCollection)</a></td><td>
Converts the specified a ListBox.ObjectCollection to a IEnumerable(T).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_AsIEnumerable__1_1">AsIEnumerable(T)(ListBox.SelectedObjectCollection)</a></td><td>
Converts the specified a ListBox.SelectedObjectCollection to a IEnumerable(T).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_CopyItem">CopyItem</a></td><td>
Copies the text of the specified item in the ListBox to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_CopyItems">CopyItems</a></td><td>
Copies the text of the specified items in the ListBox to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_CopySelectedItems">CopySelectedItems</a></td><td>
Copies the text of the current selected items in the ListBox to the clipboard.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_DeselectAllItems">DeselectAllItems</a></td><td>
Deselects all the items in ListBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_DeselectAllItemsNoJump">DeselectAllItemsNoJump</a></td><td>
Selects all the items in ListBox without scrolling to its item position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Deserialize">Deserialize</a></td><td>
Deserializes the items of the ListBox from a binary local file. 

 You can use this method to restore the items of a ListBox that were saved using the <a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Serialize">Serialize(ListBox, String, SerializationFormat)</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_MoveSelectedItems">MoveSelectedItems</a></td><td>
Moves up or down the selected items of the ListBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveDuplicates">RemoveDuplicates(ListBox)</a></td><td>
Removes duplicated items in the source ListBox, using the default EqualityComparer(T) to compare the items.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveDuplicates__1">RemoveDuplicates(T)(ListBox)</a></td><td>
Removes duplicated items of the specified Type in the source ListBox, using the default EqualityComparer(T) to compare the items.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveDuplicates__1_1">RemoveDuplicates(T)(ListBox, IEqualityComparer(T))</a></td><td>
Removes duplicated items of the specified Type in the source ListBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveEmptyOrWhiteSpaceStrings">RemoveEmptyOrWhiteSpaceStrings</a></td><td>
Removes any empty string items (String) and also string items that consists only of white-space characters in the source ListBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveEmptyStrings">RemoveEmptyStrings</a></td><td>
Removes any empty string items (String) in the source ListBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveItems__1">RemoveItems(T)</a></td><td>
Removes items of the specified Type in the source ListBox given a condition.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveSelectedItems">RemoveSelectedItems</a></td><td>
Removes the selected items from ListBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SelectAllItems">SelectAllItems</a></td><td>
Selects all the items in ListBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SelectAllItemsNoJump">SelectAllItemsNoJump</a></td><td>
Selects all the items in ListBox without scrolling to its item position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Serialize">Serialize</a></td><td>
Serializes the items of the ListBox to a binary local file. 

 You can use this method to backup the items of a ListBox, then restore them with the <a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Deserialize">Deserialize(ListBox, String, SerializationFormat)</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SetSelectedNoJump">SetSelectedNoJump(ListBox, Int32, ListBoxItemSelectionState)</a></td><td>
Selects or unselects the specified item in ListBox without scrolling to its item position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SetSelectedNoJump_1">SetSelectedNoJump(ListBox, Int32[], ListBoxItemSelectionState)</a></td><td>
Selects or unselects the specified items in ListBox without scrolling to their item positions.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SetSelectedNoJump_2">SetSelectedNoJump(ListBox, String, ListBoxItemSelectionState)</a></td><td>
Selects or unselects the specified item in ListBox without scrolling to its item position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SetSelectedNoJump_3">SetSelectedNoJump(ListBox, String[], ListBoxItemSelectionState)</a></td><td>
Selects or unselects the specified items in ListBox without scrolling to their item positions.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Sort__1">Sort(T)(ListBox)</a></td><td>
Sorts the items in the ListBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Sort__1_1">Sort(T)(ListBox, IComparer(T))</a></td><td>
Sorts the items in the ListBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_ToStringCollection">ToStringCollection</a></td><td>
Converts the specified a ListBox.ObjectCollection to a StringCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_TransferAllItems">TransferAllItems</a></td><td>
Transfers all the items from the source ListBox to another.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_ListBox_ListBoxExtensions_TransferSelectedItems">TransferSelectedItems</a></td><td>
Transfers the selected items from the source ListBox to another.</td></tr></table>&nbsp;
<a href="#listboxextensions-class">Back to Top</a>

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
<a href="#listboxextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox Namespace</a><br />