# WebUtil.DownloadFile Method (String, String, String)
 

Downloads a file to the specified filepath.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DownloadFile(
	string url,
	string dirpath,
	string filename
)
```

**VB**<br />
``` VB
Public Shared Sub DownloadFile ( 
	url As String,
	dirpath As String,
	filename As String
)
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim dirpath As String
Dim filename As StringWebUtil.DownloadFile(url, dirpath, filename)
```

**C++**<br />
``` C++
public:
static void DownloadFile(
	String^ url, 
	String^ dirpath, 
	String^ filename
)
```

**F#**<br />
``` F#
static member DownloadFile : 
        url : string * 
        dirpath : string * 
        filename : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>dirpath</dt><dd>Type: System.String<br />The target directory path.</dd><dt>filename</dt><dd>Type: System.String<br />The target filename.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
DownloadFile("http://download.thinkbroadband.com/5MB.zip", "C:\", "5MB.zip")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadFile">DownloadFile Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />