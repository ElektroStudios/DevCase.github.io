# PropertyGridInputDialog.MaximumSize Property 
 

Gets or sets the maximum size for the dialog window.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[DefaultValueAttribute(typeof(Size), "0, 0")]
public Size MaximumSize { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<DefaultValueAttribute(GetType(Size), "0, 0")>
Public Property MaximumSize As Size
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PropertyGridInputDialog
Dim value As Size

value = instance.MaximumSize

instance.MaximumSize = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[DefaultValueAttribute(typeof(Size), L"0, 0")]
property Size MaximumSize {
	Size get ();
	void set (Size value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<DefaultValueAttribute(typeof(Size), "0, 0")>]
member MaximumSize : Size with get, set

```


#### Property Value
Type: Size<br />The maximum size for the dialog window.

## See Also


#### Reference
<a href="T_DevCase_Controls_PropertyGridInputDialog">PropertyGridInputDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />