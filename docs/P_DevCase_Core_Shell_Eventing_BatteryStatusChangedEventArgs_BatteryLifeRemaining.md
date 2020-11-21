# BatteryStatusChangedEventArgs.BatteryLifeRemaining Property 
 

Gets the approximate number of seconds of battery time remaining.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int BatteryLifeRemaining { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property BatteryLifeRemaining As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As BatteryStatusChangedEventArgs
Dim value As Integer

value = instance.BatteryLifeRemaining

```

**C++**<br />
``` C++
public:
property int BatteryLifeRemaining {
	int get ();
}
```

**F#**<br />
``` F#
member BatteryLifeRemaining : int with get

```


#### Property Value
Type: Int32<br />The approximate number of seconds of battery life remaining, or `–1` if the approximate remaining battery life is unknown.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Eventing_BatteryStatusChangedEventArgs">BatteryStatusChangedEventArgs Class</a><br /><a href="N_DevCase_Core_Shell_Eventing">DevCase.Core.Shell.Eventing Namespace</a><br />