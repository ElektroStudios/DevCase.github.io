# HtmlNodeExtensions.GetNextSibling Method 
 

Gets the HTML node with the specified name immediately following this element.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_HtmlAgilityPack_Extensions_HtmlNode">DevCase.ThirdParty.HtmlAgilityPack.Extensions.HtmlNode</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static HtmlNode GetNextSibling(
	this HtmlNode sender,
	string name
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetNextSibling ( 
	sender As HtmlNode,
	name As String
) As HtmlNode
```

**VB Usage**<br />
``` VB Usage
Dim sender As HtmlNode
Dim name As String
Dim returnValue As HtmlNode

returnValue = sender.GetNextSibling(name)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static HtmlNode^ GetNextSibling(
	HtmlNode^ sender, 
	String^ name
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetNextSibling : 
        sender : HtmlNode * 
        name : string -> HtmlNode 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: HtmlNode<br />The source HtmlNode.</dd><dt>name</dt><dd>Type: System.String<br />The sibling name.</dd></dl>

#### Return Value
Type: HtmlNode<br />The resulting HtmlNode.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type HtmlNode. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_HtmlAgilityPack_Extensions_HtmlNode_HtmlNodeExtensions">HtmlNodeExtensions Class</a><br /><a href="N_DevCase_ThirdParty_HtmlAgilityPack_Extensions_HtmlNode">DevCase.ThirdParty.HtmlAgilityPack.Extensions.HtmlNode Namespace</a><br />