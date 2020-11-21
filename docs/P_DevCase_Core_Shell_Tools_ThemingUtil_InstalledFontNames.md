# ThemingUtil.InstalledFontNames Property 
 

Gets the names of the font families installed on the current machine.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> InstalledFontNames { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property InstalledFontNames As IEnumerable(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As IEnumerable(Of String)

value = ThemingUtil.InstalledFontNames

```

**C++**<br />
``` C++
public:
static property IEnumerable<String^>^ InstalledFontNames {
	IEnumerable<String^>^ get ();
}
```

**F#**<br />
``` F#
static member InstalledFontNames : IEnumerable<string> with get

```


#### Property Value
Type: IEnumerable(String)<br />The names of the font families installed on the current machine.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each fontName As String In FontNames
    Console.WriteLine(fontName)
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ThemingUtil">ThemingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />