# WebUtil.DownloadFileAsync Method (WebProxy, String, String)
 

Asynchronously downloads a file to the specified directory, using the specified proxy. 

 The filename will be retrieved from url or from MIME types. 

 If filename cannot be retrieved, a random filename will be assigned to the target filepath.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DownloadFileAsync(
	WebProxy proxy,
	string url,
	string dirpath
)
```

**VB**<br />
``` VB
Public Shared Sub DownloadFileAsync ( 
	proxy As WebProxy,
	url As String,
	dirpath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim proxy As WebProxy
Dim url As String
Dim dirpath As StringWebUtil.DownloadFileAsync(proxy, url, 
	dirpath)
```

**C++**<br />
``` C++
public:
static void DownloadFileAsync(
	WebProxy^ proxy, 
	String^ url, 
	String^ dirpath
)
```

**F#**<br />
``` F#
static member DownloadFileAsync : 
        proxy : WebProxy * 
        url : string * 
        dirpath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>dirpath</dt><dd>Type: System.String<br />The target directory path.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
proxy.Credentials = New NetworkCredential("user", "pass")
DownloadFile(proxy, "http://download.thinkbroadband.com/5MB.zip", "C:\", "5MB.zip")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadFileAsync">DownloadFileAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />