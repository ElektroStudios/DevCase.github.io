# ThemingUtil.WallpaperAsJpegIsSupported Property 
 

Gets a value that determines wheter jpeg files are supported as wallpaper in the current operating system. The jpeg wallpapers are not supported before Windows Vista.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool WallpaperAsJpegIsSupported { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property WallpaperAsJpegIsSupported As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = ThemingUtil.WallpaperAsJpegIsSupported

```

**C++**<br />
``` C++
public:
static property bool WallpaperAsJpegIsSupported {
	bool get ();
}
```

**F#**<br />
``` F#
static member WallpaperAsJpegIsSupported : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if jpeg files are supported as wallpaper in the current operating system, otherwise, `false` (`False` in Visual Basic)

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ThemingUtil">ThemingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />