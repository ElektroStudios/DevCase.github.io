# DebugUtil.IsAntiSandboxProtectionEnabled Property 
 

Gets a value that indicates whether Anti-Sandbox environment protection is enabled for the current application. 

 Anti-Sandbox environment protection can be enabled by calling <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiSandboxProtection">EnableAntiSandboxProtection(Action)</a> method, and disabled by calling <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_DisableAntiSandboxProtection">DisableAntiSandboxProtection()</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsAntiSandboxProtectionEnabled { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property IsAntiSandboxProtectionEnabled As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = DebugUtil.IsAntiSandboxProtectionEnabled

```

**C++**<br />
``` C++
public:
static property bool IsAntiSandboxProtectionEnabled {
	bool get ();
}
```

**F#**<br />
``` F#
static member IsAntiSandboxProtectionEnabled : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if Anti-Sandbox environment protection is enabled for the current application, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isEnabled As Boolean = IsAntiSandboxProtectionEnabled
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />