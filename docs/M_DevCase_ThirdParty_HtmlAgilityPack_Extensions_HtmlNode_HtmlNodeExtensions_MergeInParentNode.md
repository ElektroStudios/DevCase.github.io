# HtmlNodeExtensions.MergeInParentNode Method 
 

Merges all the nodes in the source IEnumerable(T) to a single HtmlNode.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_HtmlAgilityPack_Extensions_HtmlNode">DevCase.ThirdParty.HtmlAgilityPack.Extensions.HtmlNode</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static HtmlNode MergeInParentNode(
	this IEnumerable<HtmlNode> sender,
	string name
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function MergeInParentNode ( 
	sender As IEnumerable(Of HtmlNode),
	name As String
) As HtmlNode
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of HtmlNode)
Dim name As String
Dim returnValue As HtmlNode

returnValue = sender.MergeInParentNode(name)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static HtmlNode^ MergeInParentNode(
	IEnumerable<HtmlNode^>^ sender, 
	String^ name
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member MergeInParentNode : 
        sender : IEnumerable<HtmlNode> * 
        name : string -> HtmlNode 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(HtmlNode)<br />The source IEnumerable(T).</dd><dt>name</dt><dd>Type: System.String<br />The name of the element to create with the merged nodes.</dd></dl>

#### Return Value
Type: HtmlNode<br />The resulting HtmlNode.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(HtmlNode). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_HtmlAgilityPack_Extensions_HtmlNode_HtmlNodeExtensions">HtmlNodeExtensions Class</a><br /><a href="N_DevCase_ThirdParty_HtmlAgilityPack_Extensions_HtmlNode">DevCase.ThirdParty.HtmlAgilityPack.Extensions.HtmlNode Namespace</a><br />