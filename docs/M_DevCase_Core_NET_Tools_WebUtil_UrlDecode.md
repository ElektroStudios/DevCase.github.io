# WebUtil.UrlDecode Method 
 

Decodes a Url-encoded string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string UrlDecode(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function UrlDecode ( 
	url As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As String

returnValue = WebUtil.UrlDecode(url)
```

**C++**<br />
``` C++
public:
static String^ UrlDecode(
	String^ url
)
```

**F#**<br />
``` F#
static member UrlDecode : 
        url : string -> string 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url to decode.</dd></dl>

#### Return Value
Type: String<br />The resulting decoded Url.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim decoded As String = UrlDecode("http%3a%2f%2fwww.website.com%2fpage.asp%3fid%3d5%26test%3dHello+World")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />