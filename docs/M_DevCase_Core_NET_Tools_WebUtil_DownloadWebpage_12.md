# WebUtil.DownloadWebpage Method (Uri)
 

Downloads the source-code of an Url that points to an Html document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DownloadWebpage(
	Uri uri
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpage ( 
	uri As Uri
) As String
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim returnValue As String

returnValue = WebUtil.DownloadWebpage(uri)
```

**C++**<br />
``` C++
public:
static String^ DownloadWebpage(
	Uri^ uri
)
```

**F#**<br />
``` F#
static member DownloadWebpage : 
        uri : Uri -> string 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri address.</dd></dl>

#### Return Value
Type: String<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim html As String = DownloadWebpage(New Uri("http://www.elhacker.net/"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpage">DownloadWebpage Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />