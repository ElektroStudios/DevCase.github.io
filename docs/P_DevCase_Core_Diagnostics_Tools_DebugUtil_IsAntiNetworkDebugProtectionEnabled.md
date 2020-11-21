# DebugUtil.IsAntiNetworkDebugProtectionEnabled Property 
 

Gets a value that indicates whether Anti-Network Debugging protection is enabled for the current application. 

 Anti-Network Debugging protection can be enabled by calling <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiNetworkDebugProtection">EnableAntiNetworkDebugProtection(Action)</a> method, and disabled by calling <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_DisableAntiNetworkDebugProtection">DisableAntiNetworkDebugProtection()</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsAntiNetworkDebugProtectionEnabled { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property IsAntiNetworkDebugProtectionEnabled As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = DebugUtil.IsAntiNetworkDebugProtectionEnabled

```

**C++**<br />
``` C++
public:
static property bool IsAntiNetworkDebugProtectionEnabled {
	bool get ();
}
```

**F#**<br />
``` F#
static member IsAntiNetworkDebugProtectionEnabled : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if Anti-Network Debugging protection is enabled for the current application, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isEnabled As Boolean = IsAntiNetworkDebugProtectionEnabled
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />