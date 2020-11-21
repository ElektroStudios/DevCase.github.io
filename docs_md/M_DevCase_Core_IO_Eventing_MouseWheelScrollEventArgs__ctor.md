# MouseWheelScrollEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Eventing_MouseWheelScrollEventArgs">MouseWheelScrollEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MouseWheelScrollEventArgs(
	MouseDeviceInfo deviceInfo,
	DeviceEvent deviceEvent,
	MouseWheelDirection wheelDirection
)
```

**VB**<br />
``` VB
Public Sub New ( 
	deviceInfo As MouseDeviceInfo,
	deviceEvent As DeviceEvent,
	wheelDirection As MouseWheelDirection
)
```

**VB Usage**<br />
``` VB Usage
Dim deviceInfo As MouseDeviceInfo
Dim deviceEvent As DeviceEvent
Dim wheelDirection As MouseWheelDirection

Dim instance As New MouseWheelScrollEventArgs(deviceInfo, 
	deviceEvent, wheelDirection)
```

**C++**<br />
``` C++
public:
MouseWheelScrollEventArgs(
	MouseDeviceInfo^ deviceInfo, 
	DeviceEvent deviceEvent, 
	MouseWheelDirection wheelDirection
)
```

**F#**<br />
``` F#
new : 
        deviceInfo : MouseDeviceInfo * 
        deviceEvent : DeviceEvent * 
        wheelDirection : MouseWheelDirection -> MouseWheelScrollEventArgs
```


#### Parameters
&nbsp;<dl><dt>deviceInfo</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseDeviceInfo">DevCase.Core.IO.MouseDeviceInfo</a><br />The device data.</dd><dt>deviceEvent</dt><dd>Type: <a href="T_DevCase_Core_IO_DeviceEvent">DevCase.Core.IO.DeviceEvent</a><br />The device event.</dd><dt>wheelDirection</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseWheelDirection">DevCase.Core.IO.MouseWheelDirection</a><br />The mouse-wheel direction.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_MouseWheelScrollEventArgs">MouseWheelScrollEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />