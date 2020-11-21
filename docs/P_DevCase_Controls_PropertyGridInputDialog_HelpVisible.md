# PropertyGridInputDialog.HelpVisible Property 
 

Gets or sets a value indicating whether the Help text is visible.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(true)]
public bool HelpVisible { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(true)>
Public Property HelpVisible As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PropertyGridInputDialog
Dim value As Boolean

value = instance.HelpVisible

instance.HelpVisible = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(true)]
property bool HelpVisible {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(true)>]
member HelpVisible : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the help text is visible; otherwise, `false` (`False` in Visual Basic). The default is `true` (`True` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_PropertyGridInputDialog">PropertyGridInputDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />