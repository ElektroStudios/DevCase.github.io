# OpenFileOrFolderDialog.ShowHelp Property 
 

Gets or sets a value indicating whether the Help button is displayed in the dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(false)]
public bool ShowHelp { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(false)>
Public Property ShowHelp As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenFileOrFolderDialog
Dim value As Boolean

value = instance.ShowHelp

instance.ShowHelp = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(false)]
property bool ShowHelp {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(false)>]
member ShowHelp : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the dialog box includes a help button; otherwise, `false` (`False` in Visual Basic). 

 The default value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_OpenFileOrFolderDialog">OpenFileOrFolderDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />