# WebUtil.UrlEncode Method 
 

Encodes a Url string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string UrlEncode(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function UrlEncode ( 
	url As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As String

returnValue = WebUtil.UrlEncode(url)
```

**C++**<br />
``` C++
public:
static String^ UrlEncode(
	String^ url
)
```

**F#**<br />
``` F#
static member UrlEncode : 
        url : string -> string 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url to encode.</dd></dl>

#### Return Value
Type: String<br />The resulting encoded Url.

## Remarks
For more info, see Percent-encoding rule specifications: 

 In English: <a href="http://en.wikipedia.org/wiki/Percent-encoding" target="_blank">http://en.wikipedia.org/wiki/Percent-encoding</a>

 In Spanish: <a href="http://es.wikipedia.org/wiki/C%C3%B3digo_porciento" target="_blank">http://es.wikipedia.org/wiki/C%C3%B3digo_porciento</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim encoded As String = UrlEncode("http://www.website.com/page.asp?id=5&test=Hello World")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />