# ThemingUtil.WallpaperStylesFitFillAreSupported Property 
 

Gets a value that determines whether the <a href="T_DevCase_Core_Shell_WallpaperStyle">Fit</a> and <a href="T_DevCase_Core_Shell_WallpaperStyle">Fill</a> are supported in the current operating system. The <a href="T_DevCase_Core_Shell_WallpaperStyle">Fit</a> and <a href="T_DevCase_Core_Shell_WallpaperStyle">Fill</a> wallpaper styles are not supported before Windows 7.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool WallpaperStylesFitFillAreSupported { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property WallpaperStylesFitFillAreSupported As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = ThemingUtil.WallpaperStylesFitFillAreSupported

```

**C++**<br />
``` C++
public:
static property bool WallpaperStylesFitFillAreSupported {
	bool get ();
}
```

**F#**<br />
``` F#
static member WallpaperStylesFitFillAreSupported : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if <a href="T_DevCase_Core_Shell_WallpaperStyle">Fit</a> and <a href="T_DevCase_Core_Shell_WallpaperStyle">Fill</a> are supported in the current operating system, otherwise, `false` (`False` in Visual Basic)

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ThemingUtil">ThemingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />