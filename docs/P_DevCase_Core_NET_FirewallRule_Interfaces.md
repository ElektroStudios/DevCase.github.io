# FirewallRule.Interfaces Property 
 

Gets or sets the list of interfaces for which the rule applies. 

 The interfaces in the list are represented by their friendly name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Object Interfaces { get; set; }
```

**VB**<br />
``` VB
Public Property Interfaces As Object
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FirewallRule
Dim value As Object

value = instance.Interfaces

instance.Interfaces = value
```

**C++**<br />
``` C++
public:
property Object^ Interfaces {
	Object^ get ();
	void set (Object^ value);
}
```

**F#**<br />
``` F#
member Interfaces : Object with get, set

```


#### Property Value
Type: Object<br />The list of interfaces for which the rule applies.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa365359%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa365359%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_FirewallRule">FirewallRule Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />