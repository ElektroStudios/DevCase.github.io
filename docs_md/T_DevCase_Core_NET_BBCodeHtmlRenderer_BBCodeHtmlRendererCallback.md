# BBCodeHtmlRenderer.BBCodeHtmlRendererCallback Delegate
 

A delegate that allows you to register for your own BBCode tags. 

 This is called when the parser encounters the respective custom tag.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate string BBCodeHtmlRendererCallback(
	BBCodeNode node,
	bool throwOnError,
	Dictionary<string, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback> lookupTable
)
```

**VB**<br />
``` VB
Public Delegate Function BBCodeHtmlRendererCallback ( 
	node As BBCodeNode,
	throwOnError As Boolean,
	lookupTable As Dictionary(Of String, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback)
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As New BBCodeHtmlRendererCallback(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate String^ BBCodeHtmlRendererCallback(
	BBCodeNode^ node, 
	bool throwOnError, 
	Dictionary<String^, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback^>^ lookupTable
)
```

**F#**<br />
``` F#
type BBCodeHtmlRendererCallback = 
    delegate of 
        node : BBCodeNode * 
        throwOnError : bool * 
        lookupTable : Dictionary<string, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback> -> string
```


#### Parameters
&nbsp;<dl><dt>node</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />The node that is the custom tag.</dd><dt>throwOnError</dt><dd>Type: System.Boolean<br />True if an exception should be thrown upon error. 

 If set to false, no exceptions should be thrown and errors should be silently dealt with.</dd><dt>lookupTable</dt><dd>Type: System.Collections.Generic.Dictionary(String, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback)<br />Internal use only. 

 Must be passed on to any further ToHtml() calls.</dd></dl>

#### Return Value
Type: String<br />A string containing the HTML code for Node and all children.

## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />