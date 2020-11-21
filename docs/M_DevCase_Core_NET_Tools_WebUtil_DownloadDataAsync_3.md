# WebUtil.DownloadDataAsync Method (String, String)
 

Asynchronously downloads the specified resource as a Byte array

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<byte[]> DownloadDataAsync(
	string url,
	string userAgent
)
```

**VB**<br />
``` VB
Public Shared Function DownloadDataAsync ( 
	url As String,
	userAgent As String
) As Task(Of Byte())
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim userAgent As String
Dim returnValue As Task(Of Byte())

returnValue = WebUtil.DownloadDataAsync(url, 
	userAgent)
```

**C++**<br />
``` C++
public:
static Task<array<unsigned char>^>^ DownloadDataAsync(
	String^ url, 
	String^ userAgent
)
```

**F#**<br />
``` F#
static member DownloadDataAsync : 
        url : string * 
        userAgent : string -> Task<byte[]> 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>userAgent</dt><dd>Type: System.String<br />Specifies a custom user-agent to perform the web request.</dd></dl>

#### Return Value
Type: Task(Byte[])<br />The resource data.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim data As Byte() = Await DownloadDataAsync("http://download.thinkbroadband.com/5MB.zip", "Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.0.3705;)")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadDataAsync">DownloadDataAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />