# WebUtil.DownloadData Method (String, String)
 

Downloads the specified resource as a Byte array

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] DownloadData(
	string url,
	string userAgent
)
```

**VB**<br />
``` VB
Public Shared Function DownloadData ( 
	url As String,
	userAgent As String
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim userAgent As String
Dim returnValue As Byte()

returnValue = WebUtil.DownloadData(url, 
	userAgent)
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ DownloadData(
	String^ url, 
	String^ userAgent
)
```

**F#**<br />
``` F#
static member DownloadData : 
        url : string * 
        userAgent : string -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>userAgent</dt><dd>Type: System.String<br />Specifies a custom user-agent to perform the web request.</dd></dl>

#### Return Value
Type: Byte[]<br />The resource data.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim data As Byte() = DownloadData("http://download.thinkbroadband.com/5MB.zip", "Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.0.3705;)")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadData">DownloadData Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />