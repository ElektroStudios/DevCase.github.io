# CultureUtil.SetCurrentCulture Method (CultureInfo)
 

Sets the culture of the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetCurrentCulture(
	CultureInfo ci
)
```

**VB**<br />
``` VB
Public Shared Sub SetCurrentCulture ( 
	ci As CultureInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim ci As CultureInfoCultureUtil.SetCurrentCulture(ci)
```

**C++**<br />
``` C++
public:
static void SetCurrentCulture(
	CultureInfo^ ci
)
```

**F#**<br />
``` F#
static member SetCurrentCulture : 
        ci : CultureInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>ci</dt><dd>Type: System.Globalization.CultureInfo<br />The CultureInfo.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SetCurrentCulture(Cultures.English)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_CultureUtil">CultureUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_CultureUtil_SetCurrentCulture">SetCurrentCulture Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />