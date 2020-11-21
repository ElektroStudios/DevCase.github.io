# OpenFileOrFolderDialog.DereferenceLinks Property 
 

Gets or sets a value indicating whether the dialog box returns the location of the file referenced by the shortcut or whether it returns the location of the shortcut (.lnk).

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(true)]
public bool DereferenceLinks { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(true)>
Public Property DereferenceLinks As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenFileOrFolderDialog
Dim value As Boolean

value = instance.DereferenceLinks

instance.DereferenceLinks = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(true)]
property bool DereferenceLinks {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(true)>]
member DereferenceLinks : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the dialog box returns the location of the file referenced by the shortcut; otherwise, `false` (`False` in Visual Basic). 

 The default value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_OpenFileOrFolderDialog">OpenFileOrFolderDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />