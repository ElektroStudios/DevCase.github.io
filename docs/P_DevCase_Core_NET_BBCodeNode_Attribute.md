# BBCodeNode.Attribute Property 
 

Gets or sets this node's attribute. 

 The Attribute is the part of the tag that comes after the equals sign. 

 It is optional, and this property may return either null or an empty string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Attribute { get; set; }
```

**VB**<br />
``` VB
Public Property Attribute As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
Dim value As String

value = instance.Attribute

instance.Attribute = value
```

**C++**<br />
``` C++
public:
property String^ Attribute {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member Attribute : string with get, set

```


#### Property Value
Type: String<br />This node's attribute.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />