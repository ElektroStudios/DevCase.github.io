# FirewallRule.Profiles Property 
 

Gets or sets the profiles to which the rule belongs.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FirewallNetworkProfile Profiles { get; set; }
```

**VB**<br />
``` VB
Public Property Profiles As FirewallNetworkProfile
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FirewallRule
Dim value As FirewallNetworkProfile

value = instance.Profiles

instance.Profiles = value
```

**C++**<br />
``` C++
public:
property FirewallNetworkProfile Profiles {
	FirewallNetworkProfile get ();
	void set (FirewallNetworkProfile value);
}
```

**F#**<br />
``` F#
member Profiles : FirewallNetworkProfile with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_NET_FirewallNetworkProfile">FirewallNetworkProfile</a><br />The profiles to which the rule belongs.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa365364%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa365364%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_FirewallRule">FirewallRule Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />