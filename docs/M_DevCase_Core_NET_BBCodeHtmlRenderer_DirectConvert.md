# BBCodeHtmlRenderer.DirectConvert Method 
 

Internal method for rendering a BBCode tag that corresponds 1:1 with an HTML tag

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DirectConvert(
	BBCodeNode node,
	bool throwOnError,
	Dictionary<string, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback> lookupTable
)
```

**VB**<br />
``` VB
Public Shared Function DirectConvert ( 
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

returnValue = BBCodeHtmlRenderer.DirectConvert(node, 
	throwOnError, lookupTable)
```

**C++**<br />
``` C++
public:
static String^ DirectConvert(
	BBCodeNode^ node, 
	bool throwOnError, 
	Dictionary<String^, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback^>^ lookupTable
)
```

**F#**<br />
``` F#
static member DirectConvert : 
        node : BBCodeNode * 
        throwOnError : bool * 
        lookupTable : Dictionary<string, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback> -> string 

```


#### Parameters
&nbsp;<dl><dt>node</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />\[Missing <param name="node"/> documentation for "M:DevCase.Core.NET.BBCodeHtmlRenderer.DirectConvert(DevCase.Core.NET.BBCodeNode,System.Boolean,System.Collections.Generic.Dictionary{System.String,DevCase.Core.NET.BBCodeHtmlRenderer.BBCodeHtmlRendererCallback})"\]</dd><dt>throwOnError</dt><dd>Type: System.Boolean<br />\[Missing <param name="throwOnError"/> documentation for "M:DevCase.Core.NET.BBCodeHtmlRenderer.DirectConvert(DevCase.Core.NET.BBCodeNode,System.Boolean,System.Collections.Generic.Dictionary{System.String,DevCase.Core.NET.BBCodeHtmlRenderer.BBCodeHtmlRendererCallback})"\]</dd><dt>lookupTable</dt><dd>Type: System.Collections.Generic.Dictionary(String, <a href="T_DevCase_Core_NET_BBCodeHtmlRenderer_BBCodeHtmlRendererCallback">BBCodeHtmlRenderer.BBCodeHtmlRendererCallback</a>)<br />\[Missing <param name="lookupTable"/> documentation for "M:DevCase.Core.NET.BBCodeHtmlRenderer.DirectConvert(DevCase.Core.NET.BBCodeNode,System.Boolean,System.Collections.Generic.Dictionary{System.String,DevCase.Core.NET.BBCodeHtmlRenderer.BBCodeHtmlRendererCallback})"\]</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.Core.NET.BBCodeHtmlRenderer.DirectConvert(DevCase.Core.NET.BBCodeNode,System.Boolean,System.Collections.Generic.Dictionary{System.String,DevCase.Core.NET.BBCodeHtmlRenderer.BBCodeHtmlRendererCallback})"\]

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeHtmlRenderer">BBCodeHtmlRenderer Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />