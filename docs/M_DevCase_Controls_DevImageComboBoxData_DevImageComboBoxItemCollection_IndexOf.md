# DevImageComboBoxItemCollection.IndexOf Method (DevImageComboBoxItem)
 

Retrieves the index within the collection of the specified item.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevImageComboBoxData">DevCase.Controls.DevImageComboBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int IndexOf(
	DevImageComboBoxItem item
)
```

**VB**<br />
``` VB
Public Function IndexOf ( 
	item As DevImageComboBoxItem
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevImageComboBoxItemCollection
Dim item As DevImageComboBoxItem
Dim returnValue As Integer

returnValue = instance.IndexOf(item)
```

**C++**<br />
``` C++
public:
int IndexOf(
	DevImageComboBoxItem^ item
)
```

**F#**<br />
``` F#
member IndexOf : 
        item : DevImageComboBoxItem -> int 

```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: DevImageComboBoxItem<br />The item to locate in the collection.</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index where the item is located within the collection; otherwise, `-1`.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection">DevImageComboBoxItemCollection Class</a><br /><a href="Overload_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_IndexOf">IndexOf Overload</a><br /><a href="N_DevCase_Controls_DevImageComboBoxData">DevCase.Controls.DevImageComboBoxData Namespace</a><br />