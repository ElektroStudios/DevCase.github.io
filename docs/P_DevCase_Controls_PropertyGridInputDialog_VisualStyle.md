# PropertyGridInputDialog.VisualStyle Property 
 

Gets or sets the visual style.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(typeof(VisualStyle), "Default")]
public VisualStyle VisualStyle { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(GetType(VisualStyle), "Default")>
Public Property VisualStyle As VisualStyle
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PropertyGridInputDialog
Dim value As VisualStyle

value = instance.VisualStyle

instance.VisualStyle = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(typeof(VisualStyle), L"Default")]
property VisualStyle VisualStyle {
	VisualStyle get ();
	void set (VisualStyle value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(typeof(VisualStyle), "Default")>]
member VisualStyle : VisualStyle with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Application_UserInterface_VisualStyle">VisualStyle</a><br />The visual style. The default value is <a href="T_DevCase_Core_Application_UserInterface_VisualStyle">Default</a>.

## See Also


#### Reference
<a href="T_DevCase_Controls_PropertyGridInputDialog">PropertyGridInputDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />