# DevImageComboBoxItemCollection.IndexOf Method (String)
 

Retrieves the index within the collection of the specified item.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevImageComboBoxData">DevCase.Controls.DevImageComboBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int IndexOf(
	string text
)
```

**VB**<br />
``` VB
Public Function IndexOf ( 
	text As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevImageComboBoxItemCollection
Dim text As String
Dim returnValue As Integer

returnValue = instance.IndexOf(text)
```

**C++**<br />
``` C++
public:
int IndexOf(
	String^ text
)
```

**F#**<br />
``` F#
member IndexOf : 
        text : string -> int 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text of the item to remove from the collection.</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index where the item is located within the collection; otherwise, `-1`.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection">DevImageComboBoxItemCollection Class</a><br /><a href="Overload_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_IndexOf">IndexOf Overload</a><br /><a href="N_DevCase_Controls_DevImageComboBoxData">DevCase.Controls.DevImageComboBoxData Namespace</a><br />