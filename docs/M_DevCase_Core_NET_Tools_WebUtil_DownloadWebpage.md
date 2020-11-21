# WebUtil.DownloadWebpage Method (String)
 

Downloads the source-code of an Url that points to an Html document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DownloadWebpage(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpage ( 
	url As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As String

returnValue = WebUtil.DownloadWebpage(url)
```

**C++**<br />
``` C++
public:
static String^ DownloadWebpage(
	String^ url
)
```

**F#**<br />
``` F#
static member DownloadWebpage : 
        url : string -> string 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url address.</dd></dl>

#### Return Value
Type: String<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim html As String = DownloadWebpage("http://www.elhacker.net/")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpage">DownloadWebpage Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />