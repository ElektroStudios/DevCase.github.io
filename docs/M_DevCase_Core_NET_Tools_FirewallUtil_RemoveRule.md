# FirewallUtil.RemoveRule Method 
 

Removes a rule from Windows firewall.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveRule(
	string name
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveRule ( 
	name As String
)
```

**VB Usage**<br />
``` VB Usage
Dim name As StringFirewallUtil.RemoveRule(name)
```

**C++**<br />
``` C++
public:
static void RemoveRule(
	String^ name
)
```

**F#**<br />
``` F#
static member RemoveRule : 
        name : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The rule name.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>Windows Firewall service (MpsSvc) is not running.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_FirewallUtil">FirewallUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />