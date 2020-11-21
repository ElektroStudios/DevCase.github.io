# ThemingUtil.SetDesktopWallpaper Method 
 

Sets the current desktop wallpaper.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetDesktopWallpaper(
	string imagePath,
	WallpaperStyle style
)
```

**VB**<br />
``` VB
Public Shared Sub SetDesktopWallpaper ( 
	imagePath As String,
	style As WallpaperStyle
)
```

**VB Usage**<br />
``` VB Usage
Dim imagePath As String
Dim style As WallpaperStyleThemingUtil.SetDesktopWallpaper(imagePath, 
	style)
```

**C++**<br />
``` C++
public:
static void SetDesktopWallpaper(
	String^ imagePath, 
	WallpaperStyle style
)
```

**F#**<br />
``` F#
static member SetDesktopWallpaper : 
        imagePath : string * 
        style : WallpaperStyle -> unit 

```


#### Parameters
&nbsp;<dl><dt>imagePath</dt><dd>Type: System.String<br />The wallpaper filepath.</dd><dt>style</dt><dd>Type: <a href="T_DevCase_Core_Shell_WallpaperStyle">DevCase.Core.Shell.WallpaperStyle</a><br />The wallpaper style to apply.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>imagepath</td></tr><tr><td>InvalidEnumArgumentException</td><td>style</td></tr><tr><td>Exception</td><td>The current operating system doesn't support a fitted or filled wallpaper.</td></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ThemingUtil">ThemingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />