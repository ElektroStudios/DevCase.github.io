# TrafficChangedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_NET_Eventing_TrafficChangedEventArgs">TrafficChangedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TrafficChangedEventArgs(
	float bytesSent,
	float bytesReceived,
	float diffBytesSent,
	float diffBytesReceived
)
```

**VB**<br />
``` VB
Public Sub New ( 
	bytesSent As Single,
	bytesReceived As Single,
	diffBytesSent As Single,
	diffBytesReceived As Single
)
```

**VB Usage**<br />
``` VB Usage
Dim bytesSent As Single
Dim bytesReceived As Single
Dim diffBytesSent As Single
Dim diffBytesReceived As Single

Dim instance As New TrafficChangedEventArgs(bytesSent, 
	bytesReceived, diffBytesSent, diffBytesReceived)
```

**C++**<br />
``` C++
public:
TrafficChangedEventArgs(
	float bytesSent, 
	float bytesReceived, 
	float diffBytesSent, 
	float diffBytesReceived
)
```

**F#**<br />
``` F#
new : 
        bytesSent : float32 * 
        bytesReceived : float32 * 
        diffBytesSent : float32 * 
        diffBytesReceived : float32 -> TrafficChangedEventArgs
```


#### Parameters
&nbsp;<dl><dt>bytesSent</dt><dd>Type: System.Single<br />The bytes sent.</dd><dt>bytesReceived</dt><dd>Type: System.Single<br />The bytes received.</dd><dt>diffBytesSent</dt><dd>Type: System.Single<br />The difference between the last and the current amount of bytes sent.</dd><dt>diffBytesReceived</dt><dd>Type: System.Single<br />The difference between the last and the current amount of bytes received.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Eventing_TrafficChangedEventArgs">TrafficChangedEventArgs Class</a><br /><a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing Namespace</a><br />