# LowMemoryNotificationContext Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_LowMemoryNotificationContext">LowMemoryNotificationContext</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public LowMemoryNotificationContext(
	ulong minimum,
	Action action,
	int period = 1000
)
```

**VB**<br />
``` VB
Public Sub New ( 
	minimum As ULong,
	action As Action,
	Optional period As Integer = 1000
)
```

**VB Usage**<br />
``` VB Usage
Dim minimum As ULong
Dim action As Action
Dim period As Integer

Dim instance As New LowMemoryNotificationContext(minimum, 
	action, period)
```

**C++**<br />
``` C++
public:
LowMemoryNotificationContext(
	unsigned long long minimum, 
	Action^ action, 
	int period = 1000
)
```

**F#**<br />
``` F#
new : 
        minimum : uint64 * 
        action : Action * 
        ?period : int 
(* Defaults:
        let _period = defaultArg period 1000
*)
-> LowMemoryNotificationContext
```


#### Parameters
&nbsp;<dl><dt>minimum</dt><dd>Type: System.UInt64<br />The minimum required memory, in bytes. 

 If the total amount of free physical memory for the computer is lower than this value, the Action specified in *action* parameter will be invoked once.</dd><dt>action</dt><dd>Type: System.Action<br />The Action to invoke once if a low-memory notification occurs.</dd><dt>period (Optional)</dt><dd>Type: System.Int32<br />The time interval, in milliseconds, used to periodically check the total amount of free physical memory for the computer. 

 Default value is 1000 (1 second).</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_LowMemoryNotificationContext">LowMemoryNotificationContext Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />