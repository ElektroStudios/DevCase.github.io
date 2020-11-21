# ThemingUtil.InstalledFonts Property 
 

Gets the font families installed on the current machine.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<FontFamily> InstalledFonts { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property InstalledFonts As IEnumerable(Of FontFamily)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As IEnumerable(Of FontFamily)

value = ThemingUtil.InstalledFonts

```

**C++**<br />
``` C++
public:
static property IEnumerable<FontFamily^>^ InstalledFonts {
	IEnumerable<FontFamily^>^ get ();
}
```

**F#**<br />
``` F#
static member InstalledFonts : IEnumerable<FontFamily> with get

```


#### Property Value
Type: IEnumerable(FontFamily)<br />The font families installed on the current machine.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each fontFamily As FontFamily In Fonts
    Console.WriteLine(fontFamily.Name)
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ThemingUtil">ThemingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />