# WebUtil.ConvertHtmlPageToHtmlDocument Method 
 

Converts a string containing an Html source-code to an HtmlDocument.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static HtmlDocument ConvertHtmlPageToHtmlDocument(
	string sourceCode
)
```

**VB**<br />
``` VB
Public Shared Function ConvertHtmlPageToHtmlDocument ( 
	sourceCode As String
) As HtmlDocument
```

**VB Usage**<br />
``` VB Usage
Dim sourceCode As String
Dim returnValue As HtmlDocument

returnValue = WebUtil.ConvertHtmlPageToHtmlDocument(sourceCode)
```

**C++**<br />
``` C++
public:
static HtmlDocument^ ConvertHtmlPageToHtmlDocument(
	String^ sourceCode
)
```

**F#**<br />
``` F#
static member ConvertHtmlPageToHtmlDocument : 
        sourceCode : string -> HtmlDocument 

```


#### Parameters
&nbsp;<dl><dt>sourceCode</dt><dd>Type: System.String<br />The Html source-code.</dd></dl>

#### Return Value
Type: HtmlDocument<br />The resulting HtmlDocument instance.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim html As String = DownloadHtmlPage("http://www.elhacker.net/")
Dim htmlDoc As HtmlDocument = ConvertHtmlPageToHtmlDocument(html)
Console.WriteLine(htmlDoc.Body.OuterText)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />