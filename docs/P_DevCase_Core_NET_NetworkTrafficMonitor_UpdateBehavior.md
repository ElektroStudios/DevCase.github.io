# NetworkTrafficMonitor.UpdateBehavior Property 
 

Gets or sets a value that controls the behavior of the <a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a> event.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TrafficMonitorUpdateBehavior UpdateBehavior { get; set; }
```

**VB**<br />
``` VB
Public Property UpdateBehavior As TrafficMonitorUpdateBehavior
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As NetworkTrafficMonitor
Dim value As TrafficMonitorUpdateBehavior

value = instance.UpdateBehavior

instance.UpdateBehavior = value
```

**C++**<br />
``` C++
public:
property TrafficMonitorUpdateBehavior UpdateBehavior {
	TrafficMonitorUpdateBehavior get ();
	void set (TrafficMonitorUpdateBehavior value);
}
```

**F#**<br />
``` F#
member UpdateBehavior : TrafficMonitorUpdateBehavior with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_NET_TrafficMonitorUpdateBehavior">TrafficMonitorUpdateBehavior</a><br />A value that controls the behavior of the <a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a> event.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_NetworkTrafficMonitor">NetworkTrafficMonitor Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />