# DevListViewItemCollection.Insert Method (Int32, String, String)
 

Creates a new item with the specified text and image and inserts it in the collection at the specified index.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual ListViewItem Insert(
	int index,
	string text,
	string imageKey
)
```

**VB**<br />
``` VB
Public Overridable Function Insert ( 
	index As Integer,
	text As String,
	imageKey As String
) As ListViewItem
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListViewItemCollection
Dim index As Integer
Dim text As String
Dim imageKey As String
Dim returnValue As ListViewItem

returnValue = instance.Insert(index, text, 
	imageKey)
```

**C++**<br />
``` C++
public:
virtual ListViewItem^ Insert(
	int index, 
	String^ text, 
	String^ imageKey
)
```

**F#**<br />
``` F#
abstract Insert : 
        index : int * 
        text : string * 
        imageKey : string -> ListViewItem 
override Insert : 
        index : int * 
        text : string * 
        imageKey : string -> ListViewItem 
```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: System.Int32<br />The zero-based index location where the item is inserted.</dd><dt>text</dt><dd>Type: System.String<br />The text of the ListViewItem.</dd><dt>imageKey</dt><dd>Type: System.String<br />The key of the image to display for the item.</dd></dl>

#### Return Value
Type: ListViewItem<br />The ListViewItem added to the collection.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListViewData_DevListViewItemCollection">DevListViewItemCollection Class</a><br /><a href="Overload_DevCase_Controls_DevListViewData_DevListViewItemCollection_Insert">Insert Overload</a><br /><a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData Namespace</a><br />