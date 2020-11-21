# WebUtil.DownloadImageAsync Method (String)
 

Asynchronously downloads the specified resource as a Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<Image> DownloadImageAsync(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function DownloadImageAsync ( 
	url As String
) As Task(Of Image)
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As Task(Of Image)

returnValue = WebUtil.DownloadImageAsync(url)
```

**C++**<br />
``` C++
public:
static Task<Image^>^ DownloadImageAsync(
	String^ url
)
```

**F#**<br />
``` F#
static member DownloadImageAsync : 
        url : string -> Task<Image> 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd></dl>

#### Return Value
Type: Task(Image)<br />The resource Image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = Await DownloadImageAsync("http://i.imgur.com/EkZXp16.png")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadImageAsync">DownloadImageAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />