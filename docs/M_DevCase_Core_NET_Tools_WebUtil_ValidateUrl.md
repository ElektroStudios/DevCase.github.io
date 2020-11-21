# WebUtil.ValidateUrl Method 
 

Validates an Url. 

 Note that the source Url should be absolute, not relative.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ValidateUrl(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function ValidateUrl ( 
	url As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As Boolean

returnValue = WebUtil.ValidateUrl(url)
```

**C++**<br />
``` C++
public:
static bool ValidateUrl(
	String^ url
)
```

**F#**<br />
``` F#
static member ValidateUrl : 
        url : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the Url is valid, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isValid As Boolean = ValidateUrl("www.google.com")
Dim isValid As Boolean = ValidateUrl("http://www.google.com/")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />