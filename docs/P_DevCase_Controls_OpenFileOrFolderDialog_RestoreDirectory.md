# OpenFileOrFolderDialog.RestoreDirectory Property 
 

Gets or sets a value indicating whether the dialog box restores the directory to the previously selected directory before closing.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(false)]
public bool RestoreDirectory { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(false)>
Public Property RestoreDirectory As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenFileOrFolderDialog
Dim value As Boolean

value = instance.RestoreDirectory

instance.RestoreDirectory = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(false)]
property bool RestoreDirectory {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(false)>]
member RestoreDirectory : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the dialog box restores the current directory to the previously selected directory if the user changed the directory while searching for files; otherwise, `false` (`False` in Visual Basic). 

 The default value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_OpenFileOrFolderDialog">OpenFileOrFolderDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />