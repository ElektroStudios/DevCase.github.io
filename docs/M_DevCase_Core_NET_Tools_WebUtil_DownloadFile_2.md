# WebUtil.DownloadFile Method (String, String)
 

Downloads a file to the specified directory. 

 The filename will be retrieved from url or from MIME types. 

 If filename cannot be retrieved, a random filename will be assigned to the target filepath.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DownloadFile(
	string url,
	string dirpath
)
```

**VB**<br />
``` VB
Public Shared Sub DownloadFile ( 
	url As String,
	dirpath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim dirpath As StringWebUtil.DownloadFile(url, dirpath)
```

**C++**<br />
``` C++
public:
static void DownloadFile(
	String^ url, 
	String^ dirpath
)
```

**F#**<br />
``` F#
static member DownloadFile : 
        url : string * 
        dirpath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>dirpath</dt><dd>Type: System.String<br />The target directory path.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
DownloadFile("http://download.thinkbroadband.com/5MB.zip", "C:\")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadFile">DownloadFile Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />