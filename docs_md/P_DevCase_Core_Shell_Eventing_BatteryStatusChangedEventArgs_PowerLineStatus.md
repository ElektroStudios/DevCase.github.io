# BatteryStatusChangedEventArgs.PowerLineStatus Property 
 

Gets the current system power status.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PowerLineStatus PowerLineStatus { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property PowerLineStatus As PowerLineStatus
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As BatteryStatusChangedEventArgs
Dim value As PowerLineStatus

value = instance.PowerLineStatus

```

**C++**<br />
``` C++
public:
property PowerLineStatus PowerLineStatus {
	PowerLineStatus get ();
}
```

**F#**<br />
``` F#
member PowerLineStatus : PowerLineStatus with get

```


#### Property Value
Type: PowerLineStatus<br />One of the PowerLineStatus values indicating the current system power status.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Eventing_BatteryStatusChangedEventArgs">BatteryStatusChangedEventArgs Class</a><br /><a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing Namespace</a><br />