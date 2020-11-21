# CultureUtil.SetProcessPreferredUILanguages Method (String[])
 

Sets the preferred UI languages for the current process. 

 To retrieve the preferred UI languages for the current process, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_GetProcessPreferredUILanguages">GetProcessPreferredUILanguages()</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int SetProcessPreferredUILanguages(
	params string[] langNames
)
```

**VB**<br />
``` VB
Public Shared Function SetProcessPreferredUILanguages ( 
	ParamArray langNames As String()
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim langNames As String()
Dim returnValue As Integer

returnValue = CultureUtil.SetProcessPreferredUILanguages(langNames)
```

**C++**<br />
``` C++
public:
static int SetProcessPreferredUILanguages(
	... array<String^>^ langNames
)
```

**F#**<br />
``` F#
static member SetProcessPreferredUILanguages : 
        langNames : string[] -> int 

```


#### Parameters
&nbsp;<dl><dt>langNames</dt><dd>Type: System.String[]<br />The name of the languages, in the format languagecode2-country/regioncode2 (eg. "en-US")</dd></dl>

#### Return Value
Type: Int32<br />Returns the amount of languages that were successfully set.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim langNames As String() = {"en-US", "es-ES", "it-IT", "de-DE", "fr-FR"}
Dim successfulLangs As Integer = SetProcessPreferredUILanguages(langNames)
Console.WriteLine($"{NameOf(successfulLangs)}: {successfulLangs}")

Dim currentPreferredLangs As ReadOnlyCollection(Of CultureInfo) = GetProcessPreferredUILanguages()
Console.WriteLine($"{NameOf(currentPreferredLangs)}: {String.Join(", ", currentPreferredLangs.Select(Function(ci) ci.Name))}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_CultureUtil">CultureUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_CultureUtil_SetProcessPreferredUILanguages">SetProcessPreferredUILanguages Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />