# NetworkTrafficMonitor.InterfaceName Property 
 

Gets the name of the network interface that is being monitored.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string InterfaceName { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property InterfaceName As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As NetworkTrafficMonitor
Dim value As String

value = instance.InterfaceName

```

**C++**<br />
``` C++
public:
virtual property String^ InterfaceName {
	String^ get ();
}
```

**F#**<br />
``` F#
abstract InterfaceName : string with get
override InterfaceName : string with get
```


#### Property Value
Type: String<br />The name of the network interface that is being monitored.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_NetworkTrafficMonitor">NetworkTrafficMonitor Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />