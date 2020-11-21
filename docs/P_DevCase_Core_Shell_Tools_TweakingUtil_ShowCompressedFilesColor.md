# TweakingUtil.ShowCompressedFilesColor Property 
 

Gets or sets a value that determines whether the system will show encrypted or compressed NTFS files in different color than normal files.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ShowCompressedFilesColor { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ShowCompressedFilesColor As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ShowCompressedFilesColor

TweakingUtil.ShowCompressedFilesColor = value
```

**C++**<br />
``` C++
public:
static property bool ShowCompressedFilesColor {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ShowCompressedFilesColor : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if recycle confirmation dialog box is shown, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />