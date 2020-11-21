# PropertyGridInputDialog.PropertySort Property 
 

Gets or sets the type of sorting the property grid uses to display properties.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(3)]
public PropertySort PropertySort { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(3)>
Public Property PropertySort As PropertySort
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PropertyGridInputDialog
Dim value As PropertySort

value = instance.PropertySort

instance.PropertySort = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(3)]
property PropertySort PropertySort {
	PropertySort get ();
	void set (PropertySort value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(3)>]
member PropertySort : PropertySort with get, set

```


#### Property Value
Type: PropertySort<br />One of the PropertySort values. The default is CategorizedAlphabetical.

## See Also


#### Reference
<a href="T_DevCase_Controls_PropertyGridInputDialog">PropertyGridInputDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />