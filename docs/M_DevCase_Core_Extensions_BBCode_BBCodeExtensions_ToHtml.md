# BBCodeExtensions.ToHtml Method (BBCodeNode)
 

Converts a <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> to HTML.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_BBCode">DevCase.Core.Extensions.BBCode</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ToHtml(
	this BBCodeNode node
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function ToHtml ( 
	node As BBCodeNode
) As String
```

**VB Usage**<br />
``` VB Usage
Dim node As BBCodeNode
Dim returnValue As String

returnValue = node.ToHtml()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static String^ ToHtml(
	BBCodeNode^ node
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member ToHtml : 
        node : BBCodeNode -> string 

```


#### Parameters
&nbsp;<dl><dt>node</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />\[Missing <param name="node"/> documentation for "M:DevCase.Core.Extensions.BBCode.BBCodeExtensions.ToHtml(DevCase.Core.NET.BBCodeNode)"\]</dd></dl>

#### Return Value
Type: String<br />The HTML source as a string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_BBCode_BBCodeExtensions">BBCodeExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_BBCode_BBCodeExtensions_ToHtml">ToHtml Overload</a><br /><a href="N_DevCase_Core_Extensions_BBCode">DevCase.Core.Extensions.BBCode Namespace</a><br />