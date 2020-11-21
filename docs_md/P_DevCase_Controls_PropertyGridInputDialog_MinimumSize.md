# PropertyGridInputDialog.MinimumSize Property 
 

Gets or sets the minimum size for the dialog window.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[DefaultValueAttribute(typeof(Size), "0, 0")]
public Size MinimumSize { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<DefaultValueAttribute(GetType(Size), "0, 0")>
Public Property MinimumSize As Size
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PropertyGridInputDialog
Dim value As Size

value = instance.MinimumSize

instance.MinimumSize = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[DefaultValueAttribute(typeof(Size), L"0, 0")]
property Size MinimumSize {
	Size get ();
	void set (Size value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<DefaultValueAttribute(typeof(Size), "0, 0")>]
member MinimumSize : Size with get, set

```


#### Property Value
Type: Size<br />The minimum size for the dialog window.

## See Also


#### Reference
<a href="T_DevCase_Controls_PropertyGridInputDialog">PropertyGridInputDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />