# DebugUtil.IsRunningOnSandboxie Method 
 

Determines whether the current application is running under `Sandboxie` environment. 

`Sandboxie` is a sandbox software for application isolation, it can run a program in a virtual sandbox environment without writing to the hard drive, so, it can block malicious software, viruses, ransom-ware and zero day threats by isolating such attacks in the sandbox.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsRunningOnSandboxie()
```

**VB**<br />
``` VB
Public Shared Function IsRunningOnSandboxie As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = DebugUtil.IsRunningOnSandboxie()
```

**C++**<br />
``` C++
public:
static bool IsRunningOnSandboxie()
```

**F#**<br />
``` F#
static member IsRunningOnSandboxie : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) the current application is running under `Sandboxie` environment; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="http://www.sandboxie.com/" target="_blank">http://www.sandboxie.com/</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />