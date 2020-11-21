# WebResponseExtensions.ToHtmlNode Method 
 

Converts the source WebResponse to HtmlNode.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_HtmlAgilityPack_Extensions_WebResponse">DevCase.ThirdParty.HtmlAgilityPack.Extensions.WebResponse</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static HtmlNode ToHtmlNode(
	this WebResponse sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToHtmlNode ( 
	sender As WebResponse
) As HtmlNode
```

**VB Usage**<br />
``` VB Usage
Dim sender As WebResponse
Dim returnValue As HtmlNode

returnValue = sender.ToHtmlNode()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static HtmlNode^ ToHtmlNode(
	WebResponse^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToHtmlNode : 
        sender : WebResponse -> HtmlNode 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Net.WebResponse<br />The source WebResponse.</dd></dl>

#### Return Value
Type: HtmlNode<br />The resulting HtmlNode.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type WebResponse. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_HtmlAgilityPack_Extensions_WebResponse_WebResponseExtensions">WebResponseExtensions Class</a><br /><a href="N_DevCase_ThirdParty_HtmlAgilityPack_Extensions_WebResponse">DevCase.ThirdParty.HtmlAgilityPack.Extensions.WebResponse Namespace</a><br />