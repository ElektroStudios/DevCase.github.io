# SoftwareUtil.Steam.ClientCulture Property 
 

Gets a CultureInfo instance that represents the language of the Steam client installed on the current Operating System.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static CultureInfo ClientCulture { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ClientCulture As CultureInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As CultureInfo

value = SoftwareUtil.Steam.ClientCulture

```

**C++**<br />
``` C++
public:
static property CultureInfo^ ClientCulture {
	CultureInfo^ get ();
}
```

**F#**<br />
``` F#
static member ClientCulture : CultureInfo with get

```


#### Property Value
Type: CultureInfo<br />If Steam is not installed, the return value is `Nothing`, otherwise, a CultureInfo instance.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Steam">SoftwareUtil.Steam Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />