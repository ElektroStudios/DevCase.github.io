# ThemingUtil.IsFontInstalled Method (FontFamily)
 

Determines whether a text-font is installed on the current machine.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsFontInstalled(
	FontFamily fontFamily
)
```

**VB**<br />
``` VB
Public Shared Function IsFontInstalled ( 
	fontFamily As FontFamily
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim fontFamily As FontFamily
Dim returnValue As Boolean

returnValue = ThemingUtil.IsFontInstalled(fontFamily)
```

**C++**<br />
``` C++
public:
static bool IsFontInstalled(
	FontFamily^ fontFamily
)
```

**F#**<br />
``` F#
static member IsFontInstalled : 
        fontFamily : FontFamily -> bool 

```


#### Parameters
&nbsp;<dl><dt>fontFamily</dt><dd>Type: System.Drawing.FontFamily<br />The FontFamily.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if font is installed, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ThemingUtil">ThemingUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_ThemingUtil_IsFontInstalled">IsFontInstalled Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />