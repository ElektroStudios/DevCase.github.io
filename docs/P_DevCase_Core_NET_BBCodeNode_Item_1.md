# BBCodeNode.Item Property (String)
 

Gets an array of children <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> with the specified TagName

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public BBCodeNode[] this[
	string tagName
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Item ( 
	tagName As String
) As BBCodeNode()
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
Dim tagName As String
Dim value As BBCodeNode()

value = instance.Item(tagName)

```

**C++**<br />
``` C++
public:
property array<BBCodeNode^>^ Item[String^ tagName] {
	array<BBCodeNode^>^ get (String^ tagName);
}
```

**F#**<br />
``` F#
member Item : BBCodeNode[] with get

```


#### Parameters
&nbsp;<dl><dt>tagName</dt><dd>Type: System.String<br />The TagName of <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> to return.</dd></dl>

#### Property Value
Type: <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a>[]<br />An array of matching <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> items.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="Overload_DevCase_Core_NET_BBCodeNode_Item">Item Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />