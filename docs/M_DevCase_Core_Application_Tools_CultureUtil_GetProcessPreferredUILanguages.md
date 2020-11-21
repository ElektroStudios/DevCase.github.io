# CultureUtil.GetProcessPreferredUILanguages Method 
 

Retrieves the preferred UI languages for the current process. 

 To set the preferred UI languages for the current process, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_SetProcessPreferredUILanguages">SetProcessPreferredUILanguages(CultureInfo[])</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<CultureInfo> GetProcessPreferredUILanguages()
```

**VB**<br />
``` VB
Public Shared Function GetProcessPreferredUILanguages As ReadOnlyCollection(Of CultureInfo)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As ReadOnlyCollection(Of CultureInfo)

returnValue = CultureUtil.GetProcessPreferredUILanguages()
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<CultureInfo^>^ GetProcessPreferredUILanguages()
```

**F#**<br />
``` F#
static member GetProcessPreferredUILanguages : unit -> ReadOnlyCollection<CultureInfo> 

```


#### Return Value
Type: ReadOnlyCollection(CultureInfo)<br />The preferred UI languages for the current process. 

 Returns a null reference (`Nothing` in Visual Basic) if no preferred UI language was set for the current process.

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
<a href="T_DevCase_Core_Application_Tools_CultureUtil">CultureUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />