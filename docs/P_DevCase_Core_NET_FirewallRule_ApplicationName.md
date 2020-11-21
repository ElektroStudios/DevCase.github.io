# FirewallRule.ApplicationName Property 
 

Gets or sets the friendly name of the application to which the rule applies.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ApplicationName { get; set; }
```

**VB**<br />
``` VB
Public Property ApplicationName As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FirewallRule
Dim value As String

value = instance.ApplicationName

instance.ApplicationName = value
```

**C++**<br />
``` C++
public:
property String^ ApplicationName {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member ApplicationName : string with get, set

```


#### Property Value
Type: String<br />The friendly name of the application to which the rule applies.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa365352%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa365352%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_FirewallRule">FirewallRule Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />