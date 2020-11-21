# FirewallUtil.Enable Method (FirewallNetworkProfile)
 

Enables the Windows Firewall for the specified network profile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Enable(
	FirewallNetworkProfile profile
)
```

**VB**<br />
``` VB
Public Shared Sub Enable ( 
	profile As FirewallNetworkProfile
)
```

**VB Usage**<br />
``` VB Usage
Dim profile As FirewallNetworkProfileFirewallUtil.Enable(profile)
```

**C++**<br />
``` C++
public:
static void Enable(
	FirewallNetworkProfile profile
)
```

**F#**<br />
``` F#
static member Enable : 
        profile : FirewallNetworkProfile -> unit 

```


#### Parameters
&nbsp;<dl><dt>profile</dt><dd>Type: <a href="T_DevCase_Core_NET_FirewallNetworkProfile">DevCase.Core.NET.FirewallNetworkProfile</a><br />\[Missing <param name="profile"/> documentation for "M:DevCase.Core.NET.Tools.FirewallUtil.Enable(DevCase.Core.NET.FirewallNetworkProfile)"\]</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Windows Firewall service (MpsSvc) is not running.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_FirewallUtil">FirewallUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_FirewallUtil_Enable">Enable Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />