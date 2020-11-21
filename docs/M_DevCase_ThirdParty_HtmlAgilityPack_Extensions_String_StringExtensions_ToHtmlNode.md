# StringExtensions.ToHtmlNode Method 
 

Converts the source String to HtmlNode.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_HtmlAgilityPack_Extensions_String">DevCase.ThirdParty.HtmlAgilityPack.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static HtmlNode ToHtmlNode(
	this string sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToHtmlNode ( 
	sender As String
) As HtmlNode
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim returnValue As HtmlNode

returnValue = sender.ToHtmlNode()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static HtmlNode^ ToHtmlNode(
	String^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToHtmlNode : 
        sender : string -> HtmlNode 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd></dl>

#### Return Value
Type: HtmlNode<br />The resulting HtmlNode.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_HtmlAgilityPack_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_ThirdParty_HtmlAgilityPack_Extensions_String">DevCase.ThirdParty.HtmlAgilityPack.Extensions.String Namespace</a><br />