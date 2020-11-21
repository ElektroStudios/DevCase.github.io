# FirewallRule.Direction Property 
 

Gets or sets the direction of traffic to which the rule applies.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FirewallRuleDirection Direction { get; set; }
```

**VB**<br />
``` VB
Public Property Direction As FirewallRuleDirection
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FirewallRule
Dim value As FirewallRuleDirection

value = instance.Direction

instance.Direction = value
```

**C++**<br />
``` C++
public:
property FirewallRuleDirection Direction {
	FirewallRuleDirection get ();
	void set (FirewallRuleDirection value);
}
```

**F#**<br />
``` F#
member Direction : FirewallRuleDirection with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_NET_FirewallRuleDirection">FirewallRuleDirection</a><br />The direction of traffic to which the rule applies.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa365354%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa365354%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_FirewallRule">FirewallRule Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />