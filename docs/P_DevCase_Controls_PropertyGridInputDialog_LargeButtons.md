# PropertyGridInputDialog.LargeButtons Property 
 

Gets or sets a value indicating whether buttons appear in standard size or in large size.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(false)]
public bool LargeButtons { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(false)>
Public Property LargeButtons As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PropertyGridInputDialog
Dim value As Boolean

value = instance.LargeButtons

instance.LargeButtons = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(false)]
property bool LargeButtons {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(false)>]
member LargeButtons : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if buttons on the control appear large; otherwise, `false` (`False` in Visual Basic). The default is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_PropertyGridInputDialog">PropertyGridInputDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />