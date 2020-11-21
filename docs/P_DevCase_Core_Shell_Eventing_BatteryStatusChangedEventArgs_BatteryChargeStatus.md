# BatteryStatusChangedEventArgs.BatteryChargeStatus Property 
 

Gets the current battery charge status.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public BatteryChargeStatus BatteryChargeStatus { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property BatteryChargeStatus As BatteryChargeStatus
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As BatteryStatusChangedEventArgs
Dim value As BatteryChargeStatus

value = instance.BatteryChargeStatus

```

**C++**<br />
``` C++
public:
property BatteryChargeStatus BatteryChargeStatus {
	BatteryChargeStatus get ();
}
```

**F#**<br />
``` F#
member BatteryChargeStatus : BatteryChargeStatus with get

```


#### Property Value
Type: BatteryChargeStatus<br />One of the BatteryChargeStatus values indicating the current battery charge level or charging status.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Eventing_BatteryStatusChangedEventArgs">BatteryStatusChangedEventArgs Class</a><br /><a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing Namespace</a><br />