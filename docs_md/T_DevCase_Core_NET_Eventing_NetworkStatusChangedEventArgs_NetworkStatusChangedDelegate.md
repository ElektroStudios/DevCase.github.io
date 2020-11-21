# NetworkStatusChangedEventArgs.NetworkStatusChangedDelegate Delegate
 

Delegate NetworkStatusChangedHandler. Define the method signature for network status changes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate void NetworkStatusChangedDelegate(
	Object sender,
	NetworkStatusChangedEventArgs e
)
```

**VB**<br />
``` VB
Public Delegate Sub NetworkStatusChangedDelegate ( 
	sender As Object,
	e As NetworkStatusChangedEventArgs
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As New NetworkStatusChangedDelegate(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate void NetworkStatusChangedDelegate(
	Object^ sender, 
	NetworkStatusChangedEventArgs^ e
)
```

**F#**<br />
``` F#
type NetworkStatusChangedDelegate = 
    delegate of 
        sender : Object * 
        e : NetworkStatusChangedEventArgs -> unit
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Object<br />The source of the event.</dd><dt>e</dt><dd>Type: <a href="T_DevCase_Core_NET_Eventing_NetworkStatusChangedEventArgs">DevCase.Core.NET.Eventing.NetworkStatusChangedEventArgs</a><br />The <a href="T_DevCase_Core_NET_Eventing_NetworkStatusChangedEventArgs">NetworkStatusChangedEventArgs</a> instance containing the event data.</dd></dl>

## See Also


#### Reference
<a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing Namespace</a><br />