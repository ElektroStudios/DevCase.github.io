# MouseMoveEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Eventing_MouseMoveEventArgs">MouseMoveEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MouseMoveEventArgs(
	MouseDeviceInfo deviceInfo,
	DeviceEvent deviceEvent,
	Point position
)
```

**VB**<br />
``` VB
Public Sub New ( 
	deviceInfo As MouseDeviceInfo,
	deviceEvent As DeviceEvent,
	position As Point
)
```

**VB Usage**<br />
``` VB Usage
Dim deviceInfo As MouseDeviceInfo
Dim deviceEvent As DeviceEvent
Dim position As Point

Dim instance As New MouseMoveEventArgs(deviceInfo, 
	deviceEvent, position)
```

**C++**<br />
``` C++
public:
MouseMoveEventArgs(
	MouseDeviceInfo^ deviceInfo, 
	DeviceEvent deviceEvent, 
	Point position
)
```

**F#**<br />
``` F#
new : 
        deviceInfo : MouseDeviceInfo * 
        deviceEvent : DeviceEvent * 
        position : Point -> MouseMoveEventArgs
```


#### Parameters
&nbsp;<dl><dt>deviceInfo</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseDeviceInfo">DevCase.Core.IO.MouseDeviceInfo</a><br />The device data.</dd><dt>deviceEvent</dt><dd>Type: <a href="T_DevCase_Core_IO_DeviceEvent">DevCase.Core.IO.DeviceEvent</a><br />The device event.</dd><dt>position</dt><dd>Type: System.Drawing.Point<br />The mouse position.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_MouseMoveEventArgs">MouseMoveEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />