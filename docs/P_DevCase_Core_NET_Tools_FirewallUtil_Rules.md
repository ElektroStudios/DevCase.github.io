# FirewallUtil.Rules Property 
 

Gets the current Windows Firewall rules

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<FirewallRule> Rules { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Rules As ReadOnlyCollection(Of FirewallRule)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of FirewallRule)

value = FirewallUtil.Rules

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<FirewallRule^>^ Rules {
	ReadOnlyCollection<FirewallRule^>^ get ();
}
```

**F#**<br />
``` F#
static member Rules : ReadOnlyCollection<FirewallRule> with get

```


#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_Core_NET_FirewallRule">FirewallRule</a>)<br />The current Windows Firewall rules.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each rule As FirewallRule In FirewallUtil.Rules

    Console.WriteLine(String.Format("Name: {0}", rule.Name))
    Console.WriteLine(String.Format("Description: {0}", rule.Description))
    Console.WriteLine(String.Format("Action: {0}", rule.Action.ToString()))
    Console.WriteLine(String.Format("Direction: {0}", rule.Direction.ToString()))
    Console.WriteLine(String.Format("Protocol: {0}", rule.Protocol.ToString()))
    Console.WriteLine(String.Format("Enabled: {0}", rule.Enabled))
    Console.WriteLine()

Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_FirewallUtil">FirewallUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />