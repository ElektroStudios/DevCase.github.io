# NetworkUtil.PortScanRange Method 
 

Scans for open ports in a range of port numbers on the specified IP address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static List<int> PortScanRange(
	string address,
	int portStart,
	int portEnd,
	AddressFamily family,
	ProtocolType protocol
)
```

**VB**<br />
``` VB
Public Shared Function PortScanRange ( 
	address As String,
	portStart As Integer,
	portEnd As Integer,
	family As AddressFamily,
	protocol As ProtocolType
) As List(Of Integer)
```

**VB Usage**<br />
``` VB Usage
Dim address As String
Dim portStart As Integer
Dim portEnd As Integer
Dim family As AddressFamily
Dim protocol As ProtocolType
Dim returnValue As List(Of Integer)

returnValue = NetworkUtil.PortScanRange(address, 
	portStart, portEnd, family, protocol)
```

**C++**<br />
``` C++
public:
static List<int>^ PortScanRange(
	String^ address, 
	int portStart, 
	int portEnd, 
	AddressFamily family, 
	ProtocolType protocol
)
```

**F#**<br />
``` F#
static member PortScanRange : 
        address : string * 
        portStart : int * 
        portEnd : int * 
        family : AddressFamily * 
        protocol : ProtocolType -> List<int> 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.String<br />The IP address.</dd><dt>portStart</dt><dd>Type: System.Int32<br />The starting port number.</dd><dt>portEnd</dt><dd>Type: System.Int32<br />The ending port number.</dd><dt>family</dt><dd>Type: System.Net.Sockets.AddressFamily<br />The address family (Ipv4, Ipv6, etc).</dd><dt>protocol</dt><dd>Type: System.Net.Sockets.ProtocolType<br />The protocol type (Tcp, Udp, etc).</dd></dl>

#### Return Value
Type: List(Int32)<br />A List(T) that contains the number of the open ports.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim openPorts As List(Of Integer) = PortScanRange("localhost", 1, 1000, AddressFamily.InterNetwork, ProtocolType.Tcp)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />