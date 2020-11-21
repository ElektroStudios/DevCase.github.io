# WebUtil.DownloadData Method (String, WebProxy)
 

Downloads the specified resource as a Byte array

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] DownloadData(
	string url,
	WebProxy proxy
)
```

**VB**<br />
``` VB
Public Shared Function DownloadData ( 
	url As String,
	proxy As WebProxy
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim proxy As WebProxy
Dim returnValue As Byte()

returnValue = WebUtil.DownloadData(url, 
	proxy)
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ DownloadData(
	String^ url, 
	WebProxy^ proxy
)
```

**F#**<br />
``` F#
static member DownloadData : 
        url : string * 
        proxy : WebProxy -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd></dl>

#### Return Value
Type: Byte[]<br />The resource data.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
proxy.Credentials = New NetworkCredential("user", "pass")
Dim data As Byte() = DownloadData("http://download.thinkbroadband.com/5MB.zip", proxy)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadData">DownloadData Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />