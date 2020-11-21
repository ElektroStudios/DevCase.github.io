# FirewallUtil.FirewallServiceRunning Property 
 

Gets a value indicating whether the Windows Firewall service is enabled and running on the current machine. 

 Note that the service could be running but the Firewall itself could be disabled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool FirewallServiceRunning { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property FirewallServiceRunning As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = FirewallUtil.FirewallServiceRunning

```

**C++**<br />
``` C++
public:
static property bool FirewallServiceRunning {
	bool get ();
}
```

**F#**<br />
``` F#
static member FirewallServiceRunning : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the Windows Firewall service is running; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_FirewallUtil">FirewallUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />