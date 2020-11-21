# CultureUtil.CurrentCulture Property 
 

Gets the UI culture of the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static CultureInfo CurrentCulture { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentCulture As CultureInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As CultureInfo

value = CultureUtil.CurrentCulture

```

**C++**<br />
``` C++
public:
static property CultureInfo^ CurrentCulture {
	CultureInfo^ get ();
}
```

**F#**<br />
``` F#
static member CurrentCulture : CultureInfo with get

```


#### Property Value
Type: CultureInfo<br />The UI culture of the current thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ci As CultureInfo = CurrentCulture
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_CultureUtil">CultureUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />