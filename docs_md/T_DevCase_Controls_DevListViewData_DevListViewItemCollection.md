# DevListViewItemCollection Class
 

Represents the collection of items in a <a href="T_DevCase_Controls_DevListView">DevListView</a> control or assigned to a ListViewGroup.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Windows.Forms.ListView.ListViewItemCollection<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevListViewData.DevListViewItemCollection<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class DevListViewItemCollection : ListView.ListViewItemCollection
```

**VB**<br />
``` VB
Public Class DevListViewItemCollection
	Inherits ListView.ListViewItemCollection
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListViewItemCollection
```

**C++**<br />
``` C++
public ref class DevListViewItemCollection : public ListView.ListViewItemCollection
```

**F#**<br />
``` F#
type DevListViewItemCollection =  
    class
        inherit ListView.ListViewItemCollection
    end
```

The DevListViewItemCollection type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection__ctor">DevListViewItemCollection</a></td><td>
Initializes a new instance of the DevListViewItemCollection class.</td></tr></table>&nbsp;
<a href="#devlistviewitemcollection-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_Add">Add</a></td><td>
Adds an existing ListViewItem to the collection.
 (Overrides ListView.ListViewItemCollection.Add(ListViewItem).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_AddRange_1">AddRange(ListView.ListViewItemCollection)</a></td><td>
Adds a collection of items to the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_AddRange_2">AddRange(ListViewItem[])</a></td><td>
Adds an array of ListViewItem objects to the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_AddRange">AddRange(DevListViewItemCollection)</a></td><td>
Adds a collection of items to the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_Insert">Insert(Int32, String)</a></td><td>
Creates a new item and inserts it into the collection at the specified index.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_Insert_5">Insert(Int32, ListViewItem)</a></td><td>
Inserts an existing ListViewItem into the collection at the specified index.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_Insert_1">Insert(Int32, String, Int32)</a></td><td>
Creates a new item with the specified image index and inserts it into the collection at the specified index.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_Insert_2">Insert(Int32, String, String)</a></td><td>
Creates a new item with the specified text and image and inserts it in the collection at the specified index.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_Insert_3">Insert(Int32, String, String, Int32)</a></td><td>
Creates a new item with the specified key, text, and image, and inserts it in the collection at the specified index.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_Insert_4">Insert(Int32, String, String, String)</a></td><td>
Creates a new item with the specified key, text, and image, and adds it to the collection at the specified index.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_Remove">Remove</a></td><td>
Removes the specified item from the collection.
 (Overrides ListView.ListViewItemCollection.Remove(ListViewItem).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_RemoveAt">RemoveAt</a></td><td>
Removes the item at the specified index within the collection.
 (Overrides ListView.ListViewItemCollection.RemoveAt(Int32).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_RemoveAtRange">RemoveAtRange</a></td><td>
Removes a collection of items from the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_RemoveByKey">RemoveByKey</a></td><td>
Removes the item with the specified key from the collection.
 (Overrides ListView.ListViewItemCollection.RemoveByKey(String).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_RemoveRange_1">RemoveRange(ListView.ListViewItemCollection)</a></td><td>
Removes a collection of items from the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_RemoveRange_2">RemoveRange(ListView.SelectedListViewItemCollection)</a></td><td>
Removes a collection of selected items from the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_RemoveRange_3">RemoveRange(ListViewItem[])</a></td><td>
Removes an array of ListViewItem objects from the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevListViewData_DevListViewItemCollection_RemoveRange">RemoveRange(DevListViewItemCollection)</a></td><td>
Removes a collection of items from the collection.</td></tr></table>&nbsp;
<a href="#devlistviewitemcollection-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListViewItemCollection_ListViewItemCollectionExtensions_AsEnumerable">AsEnumerable</a></td><td>
Enumerates all the ListViewItem items in the source ListView.ListViewItemCollection collection, and returns a IEnumerable(T) collection.
 (Defined by <a href="T_DevCase_Core_Extensions_ListViewItemCollection_ListViewItemCollectionExtensions">ListViewItemCollectionExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_ListViewItemCollection_ListViewItemCollectionExtensions_ForEach">ForEach</a></td><td>
Performs the specified action on each item of the specified ListView.ListViewItemCollection collection.
 (Defined by <a href="T_DevCase_Core_Extensions_ListViewItemCollection_ListViewItemCollectionExtensions">ListViewItemCollectionExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#devlistviewitemcollection-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData Namespace</a><br />