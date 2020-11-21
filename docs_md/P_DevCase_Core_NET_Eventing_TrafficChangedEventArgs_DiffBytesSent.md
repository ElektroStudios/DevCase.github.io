# TrafficChangedEventArgs.DiffBytesSent Property 
 

Gets the difference between the last and the current amount of bytes sent. For upload speed measuring purposes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public float DiffBytesSent { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property DiffBytesSent As Single
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As TrafficChangedEventArgs
Dim value As Single

value = instance.DiffBytesSent

```

**C++**<br />
``` C++
public:
property float DiffBytesSent {
	float get ();
}
```

**F#**<br />
``` F#
member DiffBytesSent : float32 with get

```


#### Property Value
Type: Single<br />The difference between the last and the current amount of bytes sent.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Eventing_TrafficChangedEventArgs">TrafficChangedEventArgs Class</a><br /><a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing Namespace</a><br />