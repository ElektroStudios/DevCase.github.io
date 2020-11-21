# WebUtil.GetUrlFilename Method 
 

Tries to retrieve the filename of an Url that points to a file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetUrlFilename(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function GetUrlFilename ( 
	url As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As String

returnValue = WebUtil.GetUrlFilename(url)
```

**C++**<br />
``` C++
public:
static String^ GetUrlFilename(
	String^ url
)
```

**F#**<br />
``` F#
static member GetUrlFilename : 
        url : string -> string 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The source Url.</dd></dl>

#### Return Value
Type: String<br />The resulting filename.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />