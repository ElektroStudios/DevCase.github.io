# ThemingUtil.SetSystemVisualTheme Method 
 

Sets the system visual theme.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetSystemVisualTheme(
	string filePath,
	string colorName,
	string sizeName
)
```

**VB**<br />
``` VB
Public Shared Sub SetSystemVisualTheme ( 
	filePath As String,
	colorName As String,
	sizeName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim filePath As String
Dim colorName As String
Dim sizeName As StringThemingUtil.SetSystemVisualTheme(filePath, 
	colorName, sizeName)
```

**C++**<br />
``` C++
public:
static void SetSystemVisualTheme(
	String^ filePath, 
	String^ colorName, 
	String^ sizeName
)
```

**F#**<br />
``` F#
static member SetSystemVisualTheme : 
        filePath : string * 
        colorName : string * 
        sizeName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The theme file path.</dd><dt>colorName</dt><dd>Type: System.String<br />The coor scheme name.</dd><dt>sizeName</dt><dd>Type: System.String<br />The size name.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Theming.SetSystemVisualTheme("C:\ThemeName.msstyles", "NormalColor", "NormalSize")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ThemingUtil">ThemingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />