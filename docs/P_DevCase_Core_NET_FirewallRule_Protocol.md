# FirewallRule.Protocol Property 
 

Gets or sets IP protocol of the rule.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FirewallProtocol Protocol { get; set; }
```

**VB**<br />
``` VB
Public Property Protocol As FirewallProtocol
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FirewallRule
Dim value As FirewallProtocol

value = instance.Protocol

instance.Protocol = value
```

**C++**<br />
``` C++
public:
property FirewallProtocol Protocol {
	FirewallProtocol get ();
	void set (FirewallProtocol value);
}
```

**F#**<br />
``` F#
member Protocol : FirewallProtocol with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_NET_FirewallProtocol">FirewallProtocol</a><br />The IP protocol of the rule.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa365365%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa365365%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_FirewallRule">FirewallRule Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />