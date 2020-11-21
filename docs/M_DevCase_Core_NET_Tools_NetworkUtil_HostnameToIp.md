# NetworkUtil.HostnameToIp Method 
 

Gets the IP addresses that are associated to a hostname.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IPAddress[] HostnameToIp(
	string hostname,
	AddressFamily addressFamily
)
```

**VB**<br />
``` VB
Public Shared Function HostnameToIp ( 
	hostname As String,
	addressFamily As AddressFamily
) As IPAddress()
```

**VB Usage**<br />
``` VB Usage
Dim hostname As String
Dim addressFamily As AddressFamily
Dim returnValue As IPAddress()

returnValue = NetworkUtil.HostnameToIp(hostname, 
	addressFamily)
```

**C++**<br />
``` C++
public:
static array<IPAddress^>^ HostnameToIp(
	String^ hostname, 
	AddressFamily addressFamily
)
```

**F#**<br />
``` F#
static member HostnameToIp : 
        hostname : string * 
        addressFamily : AddressFamily -> IPAddress[] 

```


#### Parameters
&nbsp;<dl><dt>hostname</dt><dd>Type: System.String<br />The hostname.</dd><dt>addressFamily</dt><dd>Type: System.Net.Sockets.AddressFamily<br />The address family.</dd></dl>

#### Return Value
Type: IPAddress[]<br />The IP addresses.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NotImplementedException</td><td>Address filtering not implemented yet.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ipV4List As New List(Of String)(HostnameToIp("foro.elhacker.net", AddressFamily.InterNetwork))
Dim ipV6List As New List(Of String)(HostnameToIp("LOCALHOST", AddressFamily.InterNetworkV6))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />