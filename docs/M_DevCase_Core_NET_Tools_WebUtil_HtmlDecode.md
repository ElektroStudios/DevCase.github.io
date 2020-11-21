# WebUtil.HtmlDecode Method 
 

Converts a string that has been Html-encoded to a decoded string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string HtmlDecode(
	string str
)
```

**VB**<br />
``` VB
Public Shared Function HtmlDecode ( 
	str As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim returnValue As String

returnValue = WebUtil.HtmlDecode(str)
```

**C++**<br />
``` C++
public:
static String^ HtmlDecode(
	String^ str
)
```

**F#**<br />
``` F#
static member HtmlDecode : 
        str : string -> string 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to decode.</dd></dl>

#### Return Value
Type: String<br />The resulting decoded string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim decoded As String = HtmlDecode("I've Got A Rock 'n' Roll Heart")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />