# CultureUtil.SetThreadPreferredUILanguages Method (CultureInfo[])
 

Sets the preferred UI languages for the current thread. 

 To retrieve the preferred UI languages for the current thread, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_GetThreadPreferredUILanguages">GetThreadPreferredUILanguages()</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int SetThreadPreferredUILanguages(
	params CultureInfo[] cultures
)
```

**VB**<br />
``` VB
Public Shared Function SetThreadPreferredUILanguages ( 
	ParamArray cultures As CultureInfo()
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim cultures As CultureInfo()
Dim returnValue As Integer

returnValue = CultureUtil.SetThreadPreferredUILanguages(cultures)
```

**C++**<br />
``` C++
public:
static int SetThreadPreferredUILanguages(
	... array<CultureInfo^>^ cultures
)
```

**F#**<br />
``` F#
static member SetThreadPreferredUILanguages : 
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

Dim successfulLangs As Integer = SetThreadPreferredUILanguages(cultures)
Console.WriteLine($"{NameOf(successfulLangs)}: {successfulLangs}")

Dim currentPreferredLangs As ReadOnlyCollection(Of CultureInfo) = GetThreadPreferredUILanguages()
Console.WriteLine($"{NameOf(currentPreferredLangs)}: {String.Join(", ", currentPreferredLangs.Select(Function(ci) ci.Name))}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_CultureUtil">CultureUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_CultureUtil_SetThreadPreferredUILanguages">SetThreadPreferredUILanguages Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />