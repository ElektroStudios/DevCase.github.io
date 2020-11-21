# PowerStateMonitor.BatteryStatusChanged Event
 

Occurs when the battery status changed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<BatteryStatusChangedEventArgs> BatteryStatusChanged
```

**VB**<br />
``` VB
Public Event BatteryStatusChanged As EventHandler(Of BatteryStatusChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PowerStateMonitor
Dim handler As EventHandler(Of BatteryStatusChangedEventArgs)

AddHandler instance.BatteryStatusChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<BatteryStatusChangedEventArgs^>^ BatteryStatusChanged {
	void add (EventHandler<BatteryStatusChangedEventArgs^>^ value);
	void remove (EventHandler<BatteryStatusChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member BatteryStatusChanged : IEvent<EventHandler<BatteryStatusChangedEventArgs>,
    BatteryStatusChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_Shell_Eventing_BatteryStatusChangedEventArgs">BatteryStatusChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_PowerStateMonitor">PowerStateMonitor Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />