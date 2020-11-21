# FirewallRule.InterfaceTypes Property 
 

Gets or sets the list of interface types for which the rule applies. 

 If more than one interface type is specified, the strings must be separated by a comma.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string InterfaceTypes { get; set; }
```

**VB**<br />
``` VB
Public Property InterfaceTypes As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FirewallRule
Dim value As String

value = instance.InterfaceTypes

instance.InterfaceTypes = value
```

**C++**<br />
``` C++
public:
property String^ InterfaceTypes {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member InterfaceTypes : string with get, set

```


#### Property Value
Type: String<br />The list of interface types for which the rule applies.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa365360%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa365360%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_FirewallRule">FirewallRule Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />