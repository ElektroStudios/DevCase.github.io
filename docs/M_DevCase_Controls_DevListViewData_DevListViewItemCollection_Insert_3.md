# DevListViewItemCollection.Insert Method (Int32, String, String, Int32)
 

Creates a new item with the specified key, text, and image, and inserts it in the collection at the specified index.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual ListViewItem Insert(
	int index,
	string key,
	string text,
	int imageIndex
)
```

**VB**<br />
``` VB
Public Overridable Function Insert ( 
	index As Integer,
	key As String,
	text As String,
	imageIndex As Integer
) As ListViewItem
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListViewItemCollection
Dim index As Integer
Dim key As String
Dim text As String
Dim imageIndex As Integer
Dim returnValue As ListViewItem

returnValue = instance.Insert(index, key, 
	text, imageIndex)
```

**C++**<br />
``` C++
public:
virtual ListViewItem^ Insert(
	int index, 
	String^ key, 
	String^ text, 
	int imageIndex
)
```

**F#**<br />
``` F#
abstract Insert : 
        index : int * 
        key : string * 
        text : string * 
        imageIndex : int -> ListViewItem 
override Insert : 
        index : int * 
        key : string * 
        text : string * 
        imageIndex : int -> ListViewItem 
```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: System.Int32<br />The zero-based index location where the item is inserted</dd><dt>key</dt><dd>Type: System.String<br />The Name of the item.</dd><dt>text</dt><dd>Type: System.String<br />The text of the item.</dd><dt>imageIndex</dt><dd>Type: System.Int32<br />The index of the image to display for the item.</dd></dl>

#### Return Value
Type: ListViewItem<br />The ListViewItem added to the collection.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListViewData_DevListViewItemCollection">DevListViewItemCollection Class</a><br /><a href="Overload_DevCase_Controls_DevListViewData_DevListViewItemCollection_Insert">Insert Overload</a><br /><a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData Namespace</a><br />