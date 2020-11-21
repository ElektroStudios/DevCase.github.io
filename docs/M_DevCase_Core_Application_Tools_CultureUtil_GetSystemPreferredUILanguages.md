# CultureUtil.GetSystemPreferredUILanguages Method 
 

Retrieves the preferred UI languages for the operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<CultureInfo> GetSystemPreferredUILanguages()
```

**VB**<br />
``` VB
Public Shared Function GetSystemPreferredUILanguages As ReadOnlyCollection(Of CultureInfo)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As ReadOnlyCollection(Of CultureInfo)

returnValue = CultureUtil.GetSystemPreferredUILanguages()
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<CultureInfo^>^ GetSystemPreferredUILanguages()
```

**F#**<br />
``` F#
static member GetSystemPreferredUILanguages : unit -> ReadOnlyCollection<CultureInfo> 

```


#### Return Value
Type: ReadOnlyCollection(CultureInfo)<br />The preferred UI languages for the current process. 

 Returns a null reference (`Nothing` in Visual Basic) if no preferred UI language was set for the current process.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim currentPreferredLangs As ReadOnlyCollection(Of CultureInfo) = GetSystemPreferredUILanguages()
Console.WriteLine($"{NameOf(currentPreferredLangs)}: {String.Join(", ", currentPreferredLangs.Select(Function(ci) ci.Name))}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_CultureUtil">CultureUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />