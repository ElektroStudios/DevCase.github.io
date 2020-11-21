# BatteryStatusChangedEventArgs.BatteryFullLifetime Property 
 

Gets the reported full charge lifetime of the primary battery power source in seconds.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int BatteryFullLifetime { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property BatteryFullLifetime As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As BatteryStatusChangedEventArgs
Dim value As Integer

value = instance.BatteryFullLifetime

```

**C++**<br />
``` C++
public:
property int BatteryFullLifetime {
	int get ();
}
```

**F#**<br />
``` F#
member BatteryFullLifetime : int with get

```


#### Property Value
Type: Int32<br />The reported number of seconds of battery life available when the battery is fully charged, or `-1` if the battery life is unknown.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Eventing_BatteryStatusChangedEventArgs">BatteryStatusChangedEventArgs Class</a><br /><a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing Namespace</a><br />