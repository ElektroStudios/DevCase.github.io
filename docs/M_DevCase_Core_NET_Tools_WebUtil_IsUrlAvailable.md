# WebUtil.IsUrlAvailable Method 
 

Determines whether the specified Url is available to connect.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsUrlAvailable(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function IsUrlAvailable ( 
	url As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As Boolean

returnValue = WebUtil.IsUrlAvailable(url)
```

**C++**<br />
``` C++
public:
static bool IsUrlAvailable(
	String^ url
)
```

**F#**<br />
``` F#
static member IsUrlAvailable : 
        url : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified webpage is available to connect, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />