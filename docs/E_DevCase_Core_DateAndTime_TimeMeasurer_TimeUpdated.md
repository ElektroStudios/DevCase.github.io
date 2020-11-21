# TimeMeasurer.TimeUpdated Event
 

Occurs when the elapsed/remaining time updates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event TimeMeasurer.TimeUpdatedEventHandler TimeUpdated
```

**VB**<br />
``` VB
Public Event TimeUpdated As TimeMeasurer.TimeUpdatedEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As TimeMeasurer
Dim handler As TimeMeasurer.TimeUpdatedEventHandler

AddHandler instance.TimeUpdated, handler

```

**C++**<br />
``` C++
public:
 event TimeMeasurer.TimeUpdatedEventHandler^ TimeUpdated {
	void add (TimeMeasurer.TimeUpdatedEventHandler^ value);
	void remove (TimeMeasurer.TimeUpdatedEventHandler^ value);
}
```

**F#**<br />
``` F#
member TimeUpdated : IEvent<TimeMeasurer.TimeUpdatedEventHandler,
    TimeMeasurerUpdatedEventArgs>

```


#### Value
Type: <a href="T_DevCase_Core_DateAndTime_TimeMeasurer_TimeUpdatedEventHandler">DevCase.Core.DateAndTime.TimeMeasurer.TimeUpdatedEventHandler</a>

## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_TimeMeasurer">TimeMeasurer Class</a><br /><a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime Namespace</a><br />