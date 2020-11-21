# DebugUtil.DisableAntiSandboxProtection Method 
 

Disables the Anti-Sandbox environment protection previously enabled by <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiSandboxProtection">EnableAntiSandboxProtection(Action)</a> method for the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DisableAntiSandboxProtection()
```

**VB**<br />
``` VB
Public Shared Sub DisableAntiSandboxProtection
```

**VB Usage**<br />
``` VB Usage

DebugUtil.DisableAntiSandboxProtection()
```

**C++**<br />
``` C++
public:
static void DisableAntiSandboxProtection()
```

**F#**<br />
``` F#
static member DisableAntiSandboxProtection : unit -> unit 

```


## Examples
This is a code example. 
**VB**<br />
``` VB
Dim antiSandboxCallback As Action =
    Sub()
        Debug.WriteLine("A Sandbox environment is detected !")
        Debug.WriteLine("Disabling anti-sandbox protection...")
        DebugUtil.DisableAntiSandboxProtection
        Debug.WriteLine("Anti-sandbox protection disabled.")
    End Sub

Debug.WriteLine("Enabling anti-sandbox protection...")
DebugUtil.EnableAntiSandboxProtection(antiSandboxCallback)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />