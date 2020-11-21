# DriveWatcher.DriveStatusChanged Event
 

Occurs when a drive is inserted, removed, or changed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<DriveStatusChangedEventArgs> DriveStatusChanged
```

**VB**<br />
``` VB
Public Event DriveStatusChanged As EventHandler(Of DriveStatusChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveWatcher
Dim handler As EventHandler(Of DriveStatusChangedEventArgs)

AddHandler instance.DriveStatusChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<DriveStatusChangedEventArgs^>^ DriveStatusChanged {
	void add (EventHandler<DriveStatusChangedEventArgs^>^ value);
	void remove (EventHandler<DriveStatusChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member DriveStatusChanged : IEvent<EventHandler<DriveStatusChangedEventArgs>,
    DriveStatusChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_IO_Eventing_DriveStatusChangedEventArgs">DriveStatusChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DriveWatcher">DriveWatcher Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />