# BBCodeExtensions.ToHtml Method (BBCodeNode, Boolean, Dictionary(String, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback))
 

Converts a <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> to HTML

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_BBCode">DevCase.Core.Extensions.BBCode</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ToHtml(
	this BBCodeNode node,
	bool throwOnError,
	Dictionary<string, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback> lookupTable
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function ToHtml ( 
	node As BBCodeNode,
	throwOnError As Boolean,
	lookupTable As Dictionary(Of String, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback)
) As String
```

**VB Usage**<br />
``` VB Usage
Dim node As BBCodeNode
Dim throwOnError As Boolean
Dim lookupTable As Dictionary(Of String, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback)
Dim returnValue As String

returnValue = node.ToHtml(throwOnError, 
	lookupTable)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static String^ ToHtml(
	BBCodeNode^ node, 
	bool throwOnError, 
	Dictionary<String^, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback^>^ lookupTable
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member ToHtml : 
        node : BBCodeNode * 
        throwOnError : bool * 
        lookupTable : Dictionary<string, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback> -> string 

```


#### Parameters
&nbsp;<dl><dt>node</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />\[Missing <param name="node"/> documentation for "M:DevCase.Core.Extensions.BBCode.BBCodeExtensions.ToHtml(DevCase.Core.NET.BBCodeNode,System.Boolean,System.Collections.Generic.Dictionary{System.String,DevCase.Core.NET.BBCodeHtmlRenderer.BBCodeHtmlRendererCallback})"\]</dd><dt>throwOnError</dt><dd>Type: System.Boolean<br />A value indicating whether to throw an exception when an error is encountered. 

 If `false` (`False` in Visual Basic), errors will be silently ignored.</dd><dt>lookupTable</dt><dd>Type: System.Collections.Generic.Dictionary(String, <a href="T_DevCase_Core_NET_BBCodeHtmlRenderer_BBCodeHtmlRendererCallback">BBCodeHtmlRenderer.BBCodeHtmlRendererCallback</a>)<br />A Dictionary(TKey, TValue) containing valid BBCode tags and their HTML renderers.</dd></dl>

#### Return Value
Type: String<br />The HTML source as a string

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_BBCode_BBCodeExtensions">BBCodeExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_BBCode_BBCodeExtensions_ToHtml">ToHtml Overload</a><br /><a href="N_DevCase_Core_Extensions_BBCode">DevCase.Core.Extensions.BBCode Namespace</a><br />