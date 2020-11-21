# MouseButtonClickEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Eventing_MouseButtonClickEventArgs">MouseButtonClickEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MouseButtonClickEventArgs(
	MouseDeviceInfo deviceInfo,
	DeviceEvent deviceEvent,
	RawMouseButtons mouseButton
)
```

**VB**<br />
``` VB
Public Sub New ( 
	deviceInfo As MouseDeviceInfo,
	deviceEvent As DeviceEvent,
	mouseButton As RawMouseButtons
)
```

**VB Usage**<br />
``` VB Usage
Dim deviceInfo As MouseDeviceInfo
Dim deviceEvent As DeviceEvent
Dim mouseButton As RawMouseButtons

Dim instance As New MouseButtonClickEventArgs(deviceInfo, 
	deviceEvent, mouseButton)
```

**C++**<br />
``` C++
public:
MouseButtonClickEventArgs(
	MouseDeviceInfo^ deviceInfo, 
	DeviceEvent deviceEvent, 
	RawMouseButtons mouseButton
)
```

**F#**<br />
``` F#
new : 
        deviceInfo : MouseDeviceInfo * 
        deviceEvent : DeviceEvent * 
        mouseButton : RawMouseButtons -> MouseButtonClickEventArgs
```


#### Parameters
&nbsp;<dl><dt>deviceInfo</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseDeviceInfo">DevCase.Core.IO.MouseDeviceInfo</a><br />The device data.</dd><dt>deviceEvent</dt><dd>Type: <a href="T_DevCase_Core_IO_DeviceEvent">DevCase.Core.IO.DeviceEvent</a><br />The device event.</dd><dt>mouseButton</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RawMouseButtons">DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons</a><br />The mouse button.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_MouseButtonClickEventArgs">MouseButtonClickEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />