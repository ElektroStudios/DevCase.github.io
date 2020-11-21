# DebugUtil.EnableAntiSandboxProtection Method 
 

Enables Anti-Sandbox environment protection for the current application. 

 This Anti-Sandbox environment protection supports only these Sandbox environments: 

 • Sandboxie

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void EnableAntiSandboxProtection(
	Action callback
)
```

**VB**<br />
``` VB
Public Shared Sub EnableAntiSandboxProtection ( 
	callback As Action
)
```

**VB Usage**<br />
``` VB Usage
Dim callback As ActionDebugUtil.EnableAntiSandboxProtection(callback)
```

**C++**<br />
``` C++
public:
static void EnableAntiSandboxProtection(
	Action^ callback
)
```

**F#**<br />
``` F#
static member EnableAntiSandboxProtection : 
        callback : Action -> unit 

```


#### Parameters
&nbsp;<dl><dt>callback</dt><dd>Type: System.Action<br />An encapsulated method that will be invoked if a Sandbox environment is detected. 

 Normally it should be a method containing instructions to terminate the current application.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim antiSandboxCallback As Action =
    Sub()
        Environment.FailFast("Sandbox environment detected.")
    End Sub

DebugUtil.EnableAntiSandboxProtection(antiSandboxCallback)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />