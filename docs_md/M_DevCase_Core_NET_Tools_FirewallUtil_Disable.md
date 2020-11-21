# FirewallUtil.Disable Method 
 

Disables the Windows Firewall for the current network profile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Disable()
```

**VB**<br />
``` VB
Public Shared Sub Disable
```

**VB Usage**<br />
``` VB Usage

FirewallUtil.Disable()
```

**C++**<br />
``` C++
public:
static void Disable()
```

**F#**<br />
``` F#
static member Disable : unit -> unit 

```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Windows Firewall service (MpsSvc) is not running.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_FirewallUtil">FirewallUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_FirewallUtil_Disable">Disable Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />