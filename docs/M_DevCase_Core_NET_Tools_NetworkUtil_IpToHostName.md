# NetworkUtil.IpToHostName Method 
 

Gets the hostname that is associated to the specified IP address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string IpToHostName(
	string address
)
```

**VB**<br />
``` VB
Public Shared Function IpToHostName ( 
	address As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim address As String
Dim returnValue As String

returnValue = NetworkUtil.IpToHostName(address)
```

**C++**<br />
``` C++
public:
static String^ IpToHostName(
	String^ address
)
```

**F#**<br />
``` F#
static member IpToHostName : 
        address : string -> string 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.String<br />The IP address.</dd></dl>

#### Return Value
Type: String<br />The hostname.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />