# FirewallUtil.AddRule Method 
 

Asds a rule to Windows firewall.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AddRule(
	FirewallRule rule
)
```

**VB**<br />
``` VB
Public Shared Sub AddRule ( 
	rule As FirewallRule
)
```

**VB Usage**<br />
``` VB Usage
Dim rule As FirewallRuleFirewallUtil.AddRule(rule)
```

**C++**<br />
``` C++
public:
static void AddRule(
	FirewallRule^ rule
)
```

**F#**<br />
``` F#
static member AddRule : 
        rule : FirewallRule -> unit 

```


#### Parameters
&nbsp;<dl><dt>rule</dt><dd>Type: <a href="T_DevCase_Core_NET_FirewallRule">DevCase.Core.NET.FirewallRule</a><br />A <a href="T_DevCase_Core_NET_FirewallRule">FirewallRule</a> object containing the rule information.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Windows Firewall service (MpsSvc) is not running.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rule As New FirewallRule
With rule
    .Name = "Test rule"
    .Description = "Rule description"
    .Action = FirewallRuleAction.Block
    .Direction = FirewallRuleDirection.Inbound
    .Protocol = FirewallProtocol.Tcp
    .Enabled = True
End With

FirewallUtil.AddRule(rule)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_FirewallUtil">FirewallUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />