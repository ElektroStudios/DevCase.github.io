# NetworkTrafficMonitor.UpdateInterval Property 
 

Gets a value, in milliseconds, that determines when the monitor will update the traffic values.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual int UpdateInterval { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property UpdateInterval As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As NetworkTrafficMonitor
Dim value As Integer

value = instance.UpdateInterval

instance.UpdateInterval = value
```

**C++**<br />
``` C++
public:
virtual property int UpdateInterval {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
abstract UpdateInterval : int with get, set
override UpdateInterval : int with get, set
```


#### Property Value
Type: Int32<br />A value, in milliseconds, that determines when the monitor will update the traffic values.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_NetworkTrafficMonitor">NetworkTrafficMonitor Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />