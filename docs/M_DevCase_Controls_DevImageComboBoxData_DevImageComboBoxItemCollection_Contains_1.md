# DevImageComboBoxItemCollection.Contains Method (String)
 

Determines whether the specified item is located within the collection.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevImageComboBoxData">DevCase.Controls.DevImageComboBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Contains(
	string text
)
```

**VB**<br />
``` VB
Public Function Contains ( 
	text As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevImageComboBoxItemCollection
Dim text As String
Dim returnValue As Boolean

returnValue = instance.Contains(text)
```

**C++**<br />
``` C++
public:
bool Contains(
	String^ text
)
```

**F#**<br />
``` F#
member Contains : 
        text : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text of the item to remove from the collection.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the item is located within the collection; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection">DevImageComboBoxItemCollection Class</a><br /><a href="Overload_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_Contains">Contains Overload</a><br /><a href="N_DevCase_Controls_DevImageComboBoxData">DevCase.Controls.DevImageComboBoxData Namespace</a><br />