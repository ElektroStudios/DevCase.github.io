# NetworkUtil.TcpConnctions Property 
 

Gets the active TCP connctions.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<TcpConnectionInformation> TcpConnctions { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property TcpConnctions As IEnumerable(Of TcpConnectionInformation)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As IEnumerable(Of TcpConnectionInformation)

value = NetworkUtil.TcpConnctions

```

**C++**<br />
``` C++
public:
static property IEnumerable<TcpConnectionInformation^>^ TcpConnctions {
	IEnumerable<TcpConnectionInformation^>^ get ();
}
```

**F#**<br />
``` F#
static member TcpConnctions : IEnumerable<TcpConnectionInformation> with get

```


#### Property Value
Type: IEnumerable(TcpConnectionInformation)<br />The TCP connctions.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tcpConnections As IEnumerable(Of TcpConnectionInformation) = TcpConnctions

For Each tcpInfo As TcpConnectionInformation In tcpConnections

    Console.WriteLine("Local: {0}:{1} | Remote: {2}:{3} | State: {4}",
                      tcpInfo.LocalEndPoint.Address.ToString(), tcpInfo.LocalEndPoint.Port.ToString(),
                      tcpInfo.RemoteEndPoint.Address.ToString(), tcpInfo.RemoteEndPoint.Port.ToString(),
                      tcpInfo.State.ToString())

Next tcpInfo
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />