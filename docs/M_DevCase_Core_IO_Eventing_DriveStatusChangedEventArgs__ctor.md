# DriveStatusChangedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Eventing_DriveStatusChangedEventArgs">DriveStatusChangedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public DriveStatusChangedEventArgs(
	DeviceEvents deviceEvent,
	DriveInfo driveInfo
)
```

**VB**<br />
``` VB
Public Sub New ( 
	deviceEvent As DeviceEvents,
	driveInfo As DriveInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim deviceEvent As DeviceEvents
Dim driveInfo As DriveInfo

Dim instance As New DriveStatusChangedEventArgs(deviceEvent, 
	driveInfo)
```

**C++**<br />
``` C++
public:
DriveStatusChangedEventArgs(
	DeviceEvents deviceEvent, 
	DriveInfo^ driveInfo
)
```

**F#**<br />
``` F#
new : 
        deviceEvent : DeviceEvents * 
        driveInfo : DriveInfo -> DriveStatusChangedEventArgs
```


#### Parameters
&nbsp;<dl><dt>deviceEvent</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceEvents">DevCase.Interop.Unmanaged.Win32.Enums.DeviceEvents</a><br />\[Missing <param name="deviceEvent"/> documentation for "M:DevCase.Core.IO.Eventing.DriveStatusChangedEventArgs.#ctor(DevCase.Interop.Unmanaged.Win32.Enums.DeviceEvents,System.IO.DriveInfo)"\]</dd><dt>driveInfo</dt><dd>Type: System.IO.DriveInfo<br />The drive info.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_DriveStatusChangedEventArgs">DriveStatusChangedEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />