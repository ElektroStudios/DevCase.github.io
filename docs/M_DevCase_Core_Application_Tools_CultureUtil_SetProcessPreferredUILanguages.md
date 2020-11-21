# CultureUtil.SetProcessPreferredUILanguages Method (CultureInfo[])
 

Sets the preferred UI languages for the current process. 

 To retrieve the preferred UI languages for the current process, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_GetProcessPreferredUILanguages">GetProcessPreferredUILanguages()</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int SetProcessPreferredUILanguages(
	params CultureInfo[] cultures
)
```

**VB**<br />
``` VB
Public Shared Function SetProcessPreferredUILanguages ( 
	ParamArray cultures As CultureInfo()
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim cultures As CultureInfo()
Dim returnValue As Integer

returnValue = CultureUtil.SetProcessPreferredUILanguages(cultures)
```

**C++**<br />
``` C++
public:
static int SetProcessPreferredUILanguages(
	... array<CultureInfo^>^ cultures
)
```

**F#**<br />
``` F#
static member SetProcessPreferredUILanguages : 
        cultures : CultureInfo[] -> int 

```


#### Parameters
&nbsp;<dl><dt>cultures</dt><dd>Type: System.Globalization.CultureInfo[]<br />An array of CultureInfo representing each language.</dd></dl>

#### Return Value
Type: Int32<br />Returns the amount of languages that were successfully set.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim cultures As CultureInfo() = {
    CultureInfo.CreateSpecificCulture("en-US"),
    CultureInfo.CreateSpecificCulture("es-ES"),
    CultureInfo.CreateSpecificCulture("it-IT"),
    CultureInfo.CreateSpecificCulture("de-DE"),
    CultureInfo.CreateSpecificCulture("fr-FR")
}

Dim successfulLangs As Integer = SetProcessPreferredUILanguages(cultures)
Console.WriteLine($"{NameOf(successfulLangs)}: {successfulLangs}")

Dim currentPreferredLangs As ReadOnlyCollection(Of CultureInfo) = GetProcessPreferredUILanguages()
Console.WriteLine($"{NameOf(currentPreferredLangs)}: {String.Join(", ", currentPreferredLangs.Select(Function(ci) ci.Name))}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_CultureUtil">CultureUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_CultureUtil_SetProcessPreferredUILanguages">SetProcessPreferredUILanguages Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />