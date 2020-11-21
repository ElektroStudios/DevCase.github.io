# NetworkUtil.ValidateIp Method 
 

Validates a IP address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ValidateIp(
	string address
)
```

**VB**<br />
``` VB
Public Shared Function ValidateIp ( 
	address As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim address As String
Dim returnValue As Boolean

returnValue = NetworkUtil.ValidateIp(address)
```

**C++**<br />
``` C++
public:
static bool ValidateIp(
	String^ address
)
```

**F#**<br />
``` F#
static member ValidateIp : 
        address : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.String<br />The IP address.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the IP address is valid, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isValid As Boolean = ValidateIp("127.0.0.1")
Dim isValid As Boolean = ValidateIp("256.256.256.256")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />