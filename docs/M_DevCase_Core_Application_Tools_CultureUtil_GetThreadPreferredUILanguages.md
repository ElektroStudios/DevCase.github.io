# CultureUtil.GetThreadPreferredUILanguages Method 
 

Retrieves the preferred UI languages for the current thread. 

 To set the preferred UI languages for the current thread, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_SetThreadPreferredUILanguages">SetThreadPreferredUILanguages(CultureInfo[])</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<CultureInfo> GetThreadPreferredUILanguages()
```

**VB**<br />
``` VB
Public Shared Function GetThreadPreferredUILanguages As ReadOnlyCollection(Of CultureInfo)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As ReadOnlyCollection(Of CultureInfo)

returnValue = CultureUtil.GetThreadPreferredUILanguages()
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<CultureInfo^>^ GetThreadPreferredUILanguages()
```

**F#**<br />
``` F#
static member GetThreadPreferredUILanguages : unit -> ReadOnlyCollection<CultureInfo> 

```


#### Return Value
Type: ReadOnlyCollection(CultureInfo)<br />The preferred UI languages for the current Thread. 

 Returns a null reference (`Nothing` in Visual Basic) if no preferred UI language was set for the current Thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim langNames As String() = {"en-US", "es-ES", "it-IT", "de-DE", "fr-FR"}
Dim successfulLangs As Integer = SetThreadPreferredUILanguages(langNames)
Console.WriteLine($"{NameOf(successfulLangs)}: {successfulLangs}")

Dim currentPreferredLangs As ReadOnlyCollection(Of CultureInfo) = GetThreadPreferredUILanguages()
Console.WriteLine($"{NameOf(currentPreferredLangs)}: {String.Join(", ", currentPreferredLangs.Select(Function(ci) ci.Name))}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_CultureUtil">CultureUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />