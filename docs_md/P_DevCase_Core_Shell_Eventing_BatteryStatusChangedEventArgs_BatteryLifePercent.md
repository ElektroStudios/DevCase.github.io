# BatteryStatusChangedEventArgs.BatteryLifePercent Property 
 

Gets the approximate amount of full battery charge remaining.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public float BatteryLifePercent { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property BatteryLifePercent As Single
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As BatteryStatusChangedEventArgs
Dim value As Single

value = instance.BatteryLifePercent

```

**C++**<br />
``` C++
public:
property float BatteryLifePercent {
	float get ();
}
```

**F#**<br />
``` F#
member BatteryLifePercent : float32 with get

```


#### Property Value
Type: Single<br />The approximate amount, from `0.0` to `1.0`, of full battery charge remaining.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Eventing_BatteryStatusChangedEventArgs">BatteryStatusChangedEventArgs Class</a><br /><a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing Namespace</a><br />