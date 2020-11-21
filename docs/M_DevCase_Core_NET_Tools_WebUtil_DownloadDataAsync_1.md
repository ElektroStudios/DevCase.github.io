# WebUtil.DownloadDataAsync Method (String, WebProxy)
 

Asynchronously downloads the specified resource as a Byte array

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<byte[]> DownloadDataAsync(
	string url,
	WebProxy proxy
)
```

**VB**<br />
``` VB
Public Shared Function DownloadDataAsync ( 
	url As String,
	proxy As WebProxy
) As Task(Of Byte())
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim proxy As WebProxy
Dim returnValue As Task(Of Byte())

returnValue = WebUtil.DownloadDataAsync(url, 
	proxy)
```

**C++**<br />
``` C++
public:
static Task<array<unsigned char>^>^ DownloadDataAsync(
	String^ url, 
	WebProxy^ proxy
)
```

**F#**<br />
``` F#
static member DownloadDataAsync : 
        url : string * 
        proxy : WebProxy -> Task<byte[]> 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd></dl>

#### Return Value
Type: Task(Byte[])<br />The resource data.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
proxy.Credentials = New NetworkCredential("user", "pass")
Dim data As Byte() = Await DownloadDataAsync("http://download.thinkbroadband.com/5MB.zip", proxy)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadDataAsync">DownloadDataAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />