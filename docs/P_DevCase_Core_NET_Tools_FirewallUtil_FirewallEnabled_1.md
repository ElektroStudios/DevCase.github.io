# FirewallUtil.FirewallEnabled Property (FirewallNetworkProfile)
 

Gets a value indicating whether the Windows Firewall is enabled for the specified network profile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool this[
	FirewallNetworkProfile profile
] { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property FirewallEnabled ( 
	profile As FirewallNetworkProfile
) As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim profile As FirewallNetworkProfile
Dim value As Boolean

value = FirewallUtil.FirewallEnabled(profile)

```

**C++**<br />
``` C++
public:
static property bool FirewallEnabled[FirewallNetworkProfile profile] {
	bool get (FirewallNetworkProfile profile);
}
```

**F#**<br />
``` F#
static member FirewallEnabled : bool with get

```


#### Parameters
&nbsp;<dl><dt>profile</dt><dd>Type: <a href="T_DevCase_Core_NET_FirewallNetworkProfile">DevCase.Core.NET.FirewallNetworkProfile</a><br /></dd></dl>

#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the Windows Firewall is enabled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_FirewallUtil">FirewallUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_FirewallUtil_FirewallEnabled">FirewallEnabled Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />