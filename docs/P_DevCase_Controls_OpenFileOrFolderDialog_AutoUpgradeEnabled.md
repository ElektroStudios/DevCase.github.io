# OpenFileOrFolderDialog.AutoUpgradeEnabled Property 
 

Gets or sets a value indicating whether this dialog box should automatically upgrade appearance and behavior when running on Windows Vista.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(true)]
public bool AutoUpgradeEnabled { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(true)>
Public Property AutoUpgradeEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenFileOrFolderDialog
Dim value As Boolean

value = instance.AutoUpgradeEnabled

instance.AutoUpgradeEnabled = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(true)]
property bool AutoUpgradeEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(true)>]
member AutoUpgradeEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if this System.Windows.Forms.FileDialog instance should automatically upgrade appearance and behavior when running on Windows Vista; otherwise, `false` (`False` in Visual Basic). 

 The default value is `true` (`True` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_OpenFileOrFolderDialog">OpenFileOrFolderDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />