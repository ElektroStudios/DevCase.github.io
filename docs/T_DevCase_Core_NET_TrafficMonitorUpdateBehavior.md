# TrafficMonitorUpdateBehavior Enumeration
 

Specifies a behavior of the <a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a> and <a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a> events.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum TrafficMonitorUpdateBehavior
```

**VB**<br />
``` VB
Public Enumeration TrafficMonitorUpdateBehavior
```

**VB Usage**<br />
``` VB Usage
Dim instance As TrafficMonitorUpdateBehavior
```

**C++**<br />
``` C++
public enum class TrafficMonitorUpdateBehavior
```

**F#**<br />
``` F#
type TrafficMonitorUpdateBehavior
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.NET.TrafficMonitorUpdateBehavior.FireAlwaysAfterTick">**FireAlwaysAfterTick**</td><td>0</td><td>Fires the <a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a> event always when the specified <a href="P_DevCase_Core_NET_NetworkTrafficMonitor_UpdateInterval">UpdateInterval</a> time ticks.</td></tr><tr><td /><td target="F:DevCase.Core.NET.TrafficMonitorUpdateBehavior.FireWhenTrafficChangesAfterTick">**FireWhenTrafficChangesAfterTick**</td><td>1</td><td>Fires the <a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a> event only if received or sent bytes changes, after the specified <a href="P_DevCase_Core_NET_NetworkTrafficMonitor_UpdateInterval">UpdateInterval</a> time ticks.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />