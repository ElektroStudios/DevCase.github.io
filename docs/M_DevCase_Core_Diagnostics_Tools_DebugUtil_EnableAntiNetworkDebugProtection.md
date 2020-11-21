# DebugUtil.EnableAntiNetworkDebugProtection Method 
 

Enables Anti-Network Debugging protection for the current application. 

 This Anti-Network Debugging protection supports only these network protocol analyzers: 

 • Fiddler 

 • Wireshark 

 • WPE Pro

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void EnableAntiNetworkDebugProtection(
	Action callback
)
```

**VB**<br />
``` VB
Public Shared Sub EnableAntiNetworkDebugProtection ( 
	callback As Action
)
```

**VB Usage**<br />
``` VB Usage
Dim callback As ActionDebugUtil.EnableAntiNetworkDebugProtection(callback)
```

**C++**<br />
``` C++
public:
static void EnableAntiNetworkDebugProtection(
	Action^ callback
)
```

**F#**<br />
``` F#
static member EnableAntiNetworkDebugProtection : 
        callback : Action -> unit 

```


#### Parameters
&nbsp;<dl><dt>callback</dt><dd>Type: System.Action<br />An encapsulated method that will be invoked if a network debugger is detected. 

 Normally it should be a method containing instructions to terminate the current application.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim antiNetworkDebugCallback As Action =
    Sub()
        Environment.FailFast("Network debugger detected.")
    End Sub

DebugUtil.EnableAntiNetworkDebugProtection(antiNetworkDebugCallback)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />