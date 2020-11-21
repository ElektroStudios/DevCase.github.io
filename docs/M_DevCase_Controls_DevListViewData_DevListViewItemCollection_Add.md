# DevListViewItemCollection.Add Method 
 

Adds an existing ListViewItem to the collection.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override ListViewItem Add(
	ListViewItem value
)
```

**VB**<br />
``` VB
Public Overrides Function Add ( 
	value As ListViewItem
) As ListViewItem
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListViewItemCollection
Dim value As ListViewItem
Dim returnValue As ListViewItem

returnValue = instance.Add(value)
```

**C++**<br />
``` C++
public:
virtual ListViewItem^ Add(
	ListViewItem^ value
) override
```

**F#**<br />
``` F#
abstract Add : 
        value : ListViewItem -> ListViewItem 
override Add : 
        value : ListViewItem -> ListViewItem 
```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.Windows.Forms.ListViewItem<br />The ListViewItem to add to the collection.</dd></dl>

#### Return Value
Type: ListViewItem<br />The ListViewItem that was added to the collection.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListViewData_DevListViewItemCollection">DevListViewItemCollection Class</a><br /><a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData Namespace</a><br />