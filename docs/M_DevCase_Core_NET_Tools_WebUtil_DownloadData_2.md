# WebUtil.DownloadData Method (String, WebProxy, String)
 

Downloads the specified resource as a Byte array

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] DownloadData(
	string url,
	WebProxy proxy,
	string userAgent
)
```

**VB**<br />
``` VB
Public Shared Function DownloadData ( 
	url As String,
	proxy As WebProxy,
	userAgent As String
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim proxy As WebProxy
Dim userAgent As String
Dim returnValue As Byte()

returnValue = WebUtil.DownloadData(url, 
	proxy, userAgent)
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ DownloadData(
	String^ url, 
	WebProxy^ proxy, 
	String^ userAgent
)
```

**F#**<br />
``` F#
static member DownloadData : 
        url : string * 
        proxy : WebProxy * 
        userAgent : string -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd><dt>userAgent</dt><dd>Type: System.String<br />Specifies a custom user-agent to perform the web request.</dd></dl>

#### Return Value
Type: Byte[]<br />The resource data.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
proxy.Credentials = New NetworkCredential("user", "pass")
Dim data As Byte() = DownloadData("http://download.thinkbroadband.com/5MB.zip", proxy, "Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.0.3705;)")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadData">DownloadData Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />