# BBCodeHtmlRenderer.DefaultLookupTable Property 
 

Gets the default lookup table. 

 Contains renderers for [b], [i], [u], [code], [del], [ins], [hr], [body], [img] and [a] tags.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Dictionary<string, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback> DefaultLookupTable { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property DefaultLookupTable As Dictionary(Of String, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Dictionary(Of String, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback)

value = BBCodeHtmlRenderer.DefaultLookupTable

```

**C++**<br />
``` C++
public:
static property Dictionary<String^, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback^>^ DefaultLookupTable {
	Dictionary<String^, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback^>^ get ();
}
```

**F#**<br />
``` F#
static member DefaultLookupTable : Dictionary<string, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback> with get

```


#### Property Value
Type: Dictionary(String, <a href="T_DevCase_Core_NET_BBCodeHtmlRenderer_BBCodeHtmlRendererCallback">BBCodeHtmlRenderer.BBCodeHtmlRendererCallback</a>)<br />The default lookup table.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeHtmlRenderer">BBCodeHtmlRenderer Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />