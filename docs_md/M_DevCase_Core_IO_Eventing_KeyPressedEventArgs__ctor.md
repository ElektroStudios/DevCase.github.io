# KeyPressedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Eventing_KeyPressedEventArgs">KeyPressedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public KeyPressedEventArgs(
	KeyboardDeviceInfo deviceInfo,
	DeviceEvent deviceEvent
)
```

**VB**<br />
``` VB
Public Sub New ( 
	deviceInfo As KeyboardDeviceInfo,
	deviceEvent As DeviceEvent
)
```

**VB Usage**<br />
``` VB Usage
Dim deviceInfo As KeyboardDeviceInfo
Dim deviceEvent As DeviceEvent

Dim instance As New KeyPressedEventArgs(deviceInfo, 
	deviceEvent)
```

**C++**<br />
``` C++
public:
KeyPressedEventArgs(
	KeyboardDeviceInfo^ deviceInfo, 
	DeviceEvent deviceEvent
)
```

**F#**<br />
``` F#
new : 
        deviceInfo : KeyboardDeviceInfo * 
        deviceEvent : DeviceEvent -> KeyPressedEventArgs
```


#### Parameters
&nbsp;<dl><dt>deviceInfo</dt><dd>Type: <a href="T_DevCase_Core_IO_KeyboardDeviceInfo">DevCase.Core.IO.KeyboardDeviceInfo</a><br />The device data.</dd><dt>deviceEvent</dt><dd>Type: <a href="T_DevCase_Core_IO_DeviceEvent">DevCase.Core.IO.DeviceEvent</a><br />The device event.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_KeyPressedEventArgs">KeyPressedEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />