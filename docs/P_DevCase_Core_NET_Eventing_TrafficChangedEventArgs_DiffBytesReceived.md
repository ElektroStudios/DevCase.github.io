# TrafficChangedEventArgs.DiffBytesReceived Property 
 

Gets the difference between the last and the current amount of bytes received. For download speed measuring purposes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public float DiffBytesReceived { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property DiffBytesReceived As Single
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As TrafficChangedEventArgs
Dim value As Single

value = instance.DiffBytesReceived

```

**C++**<br />
``` C++
public:
property float DiffBytesReceived {
	float get ();
}
```

**F#**<br />
``` F#
member DiffBytesReceived : float32 with get

```


#### Property Value
Type: Single<br />The difference between the last and the current amount of bytes received.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Eventing_TrafficChangedEventArgs">TrafficChangedEventArgs Class</a><br /><a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing Namespace</a><br />