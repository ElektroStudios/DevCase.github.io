# WebUtil.GetResponseFilename Method 
 

Tries to retrieve the filename of a WebResponse that points to a file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetResponseFilename(
	WebResponse resp
)
```

**VB**<br />
``` VB
Public Shared Function GetResponseFilename ( 
	resp As WebResponse
) As String
```

**VB Usage**<br />
``` VB Usage
Dim resp As WebResponse
Dim returnValue As String

returnValue = WebUtil.GetResponseFilename(resp)
```

**C++**<br />
``` C++
public:
static String^ GetResponseFilename(
	WebResponse^ resp
)
```

**F#**<br />
``` F#
static member GetResponseFilename : 
        resp : WebResponse -> string 

```


#### Parameters
&nbsp;<dl><dt>resp</dt><dd>Type: System.Net.WebResponse<br />The source WebResponse.</dd></dl>

#### Return Value
Type: String<br />The resulting filename.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />