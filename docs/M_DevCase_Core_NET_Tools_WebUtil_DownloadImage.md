# WebUtil.DownloadImage Method (String)
 

Downloads the specified resource as a Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image DownloadImage(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function DownloadImage ( 
	url As String
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As Image

returnValue = WebUtil.DownloadImage(url)
```

**C++**<br />
``` C++
public:
static Image^ DownloadImage(
	String^ url
)
```

**F#**<br />
``` F#
static member DownloadImage : 
        url : string -> Image 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd></dl>

#### Return Value
Type: Image<br />The resource Image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = DownloadImage("http://i.imgur.com/EkZXp16.png")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadImage">DownloadImage Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />