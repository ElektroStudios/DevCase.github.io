# DevProgressDialog.CompactStrings Property 
 

Gets or sets a value indicating whether to compact displayed strings if they are too large to fit on a line.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(false)]
public bool CompactStrings { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(false)>
Public Property CompactStrings As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
Dim value As Boolean

value = instance.CompactStrings

instance.CompactStrings = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(false)]
property bool CompactStrings {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(false)>]
member CompactStrings : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) to have path strings compacted if they are too large to fit on a line.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressDialog">DevProgressDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />