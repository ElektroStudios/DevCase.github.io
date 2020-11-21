# HtmlAgilityPackUtil.GetHtmlXPaths Method 
 

Gets a collection containing all the X-Path expressions of an HtmlDocument document.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_HtmlAgilityPack">DevCase.ThirdParty.HtmlAgilityPack</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<string> GetHtmlXPaths(
	HtmlDocument document
)
```

**VB**<br />
``` VB
Public Shared Function GetHtmlXPaths ( 
	document As HtmlDocument
) As ReadOnlyCollection(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim document As HtmlDocument
Dim returnValue As ReadOnlyCollection(Of String)

returnValue = HtmlAgilityPackUtil.GetHtmlXPaths(document)
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<String^>^ GetHtmlXPaths(
	HtmlDocument^ document
)
```

**F#**<br />
``` F#
static member GetHtmlXPaths : 
        document : HtmlDocument -> ReadOnlyCollection<string> 

```


#### Parameters
&nbsp;<dl><dt>document</dt><dd>Type: HtmlDocument<br />The HtmlDocument document.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(String)<br />A collection containing all the X-Path expressions of an HtmlDocument document.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim document As New HtmlAgilityPack.HtmlDocument
document.LoadHtml(File.ReadAllText("C:\File.html"))
Dim xpathList As ReadOnlyCollection(Of String) = GetHtmlXPaths(document)
ListBox1.Items.AddRange((From XPath As String In xpathList Select XPath).ToArray())
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_HtmlAgilityPack_HtmlAgilityPackUtil">HtmlAgilityPackUtil Class</a><br /><a href="N_DevCase_ThirdParty_HtmlAgilityPack">DevCase.ThirdParty.HtmlAgilityPack Namespace</a><br />