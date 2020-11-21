# DriveStatusChangedEventArgs.DeviceEvent Property 
 

Gets the device event that occurred.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public DeviceEvents DeviceEvent { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property DeviceEvent As DeviceEvents
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveStatusChangedEventArgs
Dim value As DeviceEvents

value = instance.DeviceEvent

```

**C++**<br />
``` C++
public:
property DeviceEvents DeviceEvent {
	DeviceEvents get ();
}
```

**F#**<br />
``` F#
member DeviceEvent : DeviceEvents with get

```


#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceEvents">DeviceEvents</a><br />The drive info.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_DriveStatusChangedEventArgs">DriveStatusChangedEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />