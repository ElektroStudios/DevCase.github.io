# NetworkUtil.PortScan Method 
 

Scans for a open port on the specified IP address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool PortScan(
	string address,
	int port,
	AddressFamily family,
	ProtocolType protocol
)
```

**VB**<br />
``` VB
Public Shared Function PortScan ( 
	address As String,
	port As Integer,
	family As AddressFamily,
	protocol As ProtocolType
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim address As String
Dim port As Integer
Dim family As AddressFamily
Dim protocol As ProtocolType
Dim returnValue As Boolean

returnValue = NetworkUtil.PortScan(address, 
	port, family, protocol)
```

**C++**<br />
``` C++
public:
static bool PortScan(
	String^ address, 
	int port, 
	AddressFamily family, 
	ProtocolType protocol
)
```

**F#**<br />
``` F#
static member PortScan : 
        address : string * 
        port : int * 
        family : AddressFamily * 
        protocol : ProtocolType -> bool 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.String<br />The IP address.</dd><dt>port</dt><dd>Type: System.Int32<br />The port number.</dd><dt>family</dt><dd>Type: System.Net.Sockets.AddressFamily<br />The address family (Ipv4, Ipv6, etc).</dd><dt>protocol</dt><dd>Type: System.Net.Sockets.ProtocolType<br />The protocol type (Tcp, Udp, etc).</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if port is open, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isOpen As Boolean = PortScan("localhost", 80, AddressFamily.InterNetwork, ProtocolType.Udp)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />