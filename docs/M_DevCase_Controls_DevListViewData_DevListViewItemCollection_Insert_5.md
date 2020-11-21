# DevListViewItemCollection.Insert Method (Int32, ListViewItem)
 

Inserts an existing ListViewItem into the collection at the specified index.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual ListViewItem Insert(
	int index,
	ListViewItem item
)
```

**VB**<br />
``` VB
Public Overridable Function Insert ( 
	index As Integer,
	item As ListViewItem
) As ListViewItem
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListViewItemCollection
Dim index As Integer
Dim item As ListViewItem
Dim returnValue As ListViewItem

returnValue = instance.Insert(index, item)
```

**C++**<br />
``` C++
public:
virtual ListViewItem^ Insert(
	int index, 
	ListViewItem^ item
)
```

**F#**<br />
``` F#
abstract Insert : 
        index : int * 
        item : ListViewItem -> ListViewItem 
override Insert : 
        index : int * 
        item : ListViewItem -> ListViewItem 
```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: System.Int32<br />The zero-based index location where the item is inserted.</dd><dt>item</dt><dd>Type: System.Windows.Forms.ListViewItem<br />The ListViewItem that represents the item to insert.</dd></dl>

#### Return Value
Type: ListViewItem<br />The ListViewItem that was inserted into the collection.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListViewData_DevListViewItemCollection">DevListViewItemCollection Class</a><br /><a href="Overload_DevCase_Controls_DevListViewData_DevListViewItemCollection_Insert">Insert Overload</a><br /><a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData Namespace</a><br />