# DebugUtil.DisableAntiNetworkDebugProtection Method 
 

Disables the Anti-Network Debugging protection previously enabled by <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiNetworkDebugProtection">EnableAntiNetworkDebugProtection(Action)</a> method for the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DisableAntiNetworkDebugProtection()
```

**VB**<br />
``` VB
Public Shared Sub DisableAntiNetworkDebugProtection
```

**VB Usage**<br />
``` VB Usage

DebugUtil.DisableAntiNetworkDebugProtection()
```

**C++**<br />
``` C++
public:
static void DisableAntiNetworkDebugProtection()
```

**F#**<br />
``` F#
static member DisableAntiNetworkDebugProtection : unit -> unit 

```


## Examples
This is a code example. 
**VB**<br />
``` VB
Dim antiNetworkDebugCallback As Action =
    Sub()
        Debug.WriteLine("A network debugger is detected!")
        Debug.WriteLine("Disabling anti-network debugging protection...")
        DebugUtil.DisableAntiNetworkDebugProtection
        Debug.WriteLine("Anti-network debugging protection disabled.")
    End Sub

Debug.WriteLine("Enabling anti-network debugging protection...")
DebugUtil.EnableAntiNetworkDebugProtection(antiNetworkDebugCallback)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />