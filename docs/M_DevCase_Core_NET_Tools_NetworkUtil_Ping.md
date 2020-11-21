# NetworkUtil.Ping Method 
 

Pings the specified address or hostname to determine whether a remote computer is accessible over the network.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Ping(
	string address,
	int timeOut = 1000,
	byte[] bufferData = null,
	bool fragmentData = false,
	int timeToLive = 128
)
```

**VB**<br />
``` VB
Public Shared Function Ping ( 
	address As String,
	Optional timeOut As Integer = 1000,
	Optional bufferData As Byte() = Nothing,
	Optional fragmentData As Boolean = false,
	Optional timeToLive As Integer = 128
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim address As String
Dim timeOut As Integer
Dim bufferData As Byte()
Dim fragmentData As Boolean
Dim timeToLive As Integer
Dim returnValue As Boolean

returnValue = NetworkUtil.Ping(address, 
	timeOut, bufferData, fragmentData, 
	timeToLive)
```

**C++**<br />
``` C++
public:
static bool Ping(
	String^ address, 
	int timeOut = 1000, 
	array<unsigned char>^ bufferData = nullptr, 
	bool fragmentData = false, 
	int timeToLive = 128
)
```

**F#**<br />
``` F#
static member Ping : 
        address : string * 
        ?timeOut : int * 
        ?bufferData : byte[] * 
        ?fragmentData : bool * 
        ?timeToLive : int 
(* Defaults:
        let _timeOut = defaultArg timeOut 1000
        let _bufferData = defaultArg bufferData null
        let _fragmentData = defaultArg fragmentData false
        let _timeToLive = defaultArg timeToLive 128
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.String<br />The computer that is the destination for the ICMP echo message. 

 The value specified for this parameter can be a hostname or an IP address.</dd><dt>timeOut (Optional)</dt><dd>Type: System.Int32<br />The maximum number of milliseconds (after sending the echo message) to wait for the ICMP echo reply message. Default value is `200`.</dd><dt>bufferData (Optional)</dt><dd>Type: System.Byte[]<br />The data to be sent with the ICMP echo message and returned in the ICMP echo reply message. 

 The array cannot contain more than 65,500 bytes.</dd><dt>fragmentData (Optional)</dt><dd>Type: System.Boolean<br />Controls the fragmentation of the data sent to the remote host. 

 If set to `true` (`True` in Visual Basic), the data is sent in multiple packets. Default value is `false` (`False` in Visual Basic).</dd><dt>timeToLive (Optional)</dt><dd>Type: System.Int32<br />The number of routing nodes that can forward the Ping data before it is discarded. 

 Default value is `128`.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if ping operation success, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isAvailable As Boolean = Ping("www.google.com")

Dim isAvailable As Boolean =
    Ping("www.google.com", timeOut:=1000, bufferData:=Encoding.ASCII.GetBytes("Hello"), fragmentData:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />