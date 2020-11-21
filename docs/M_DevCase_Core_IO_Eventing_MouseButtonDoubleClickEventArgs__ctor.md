# MouseButtonDoubleClickEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Eventing_MouseButtonDoubleClickEventArgs">MouseButtonDoubleClickEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MouseButtonDoubleClickEventArgs(
	MouseDeviceInfo deviceInfo,
	DeviceEvent deviceEvent,
	MouseButtons mouseButton
)
```

**VB**<br />
``` VB
Public Sub New ( 
	deviceInfo As MouseDeviceInfo,
	deviceEvent As DeviceEvent,
	mouseButton As MouseButtons
)
```

**VB Usage**<br />
``` VB Usage
Dim deviceInfo As MouseDeviceInfo
Dim deviceEvent As DeviceEvent
Dim mouseButton As MouseButtons

Dim instance As New MouseButtonDoubleClickEventArgs(deviceInfo, 
	deviceEvent, mouseButton)
```

**C++**<br />
``` C++
public:
MouseButtonDoubleClickEventArgs(
	MouseDeviceInfo^ deviceInfo, 
	DeviceEvent deviceEvent, 
	MouseButtons mouseButton
)
```

**F#**<br />
``` F#
new : 
        deviceInfo : MouseDeviceInfo * 
        deviceEvent : DeviceEvent * 
        mouseButton : MouseButtons -> MouseButtonDoubleClickEventArgs
```


#### Parameters
&nbsp;<dl><dt>deviceInfo</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseDeviceInfo">DevCase.Core.IO.MouseDeviceInfo</a><br />The device data.</dd><dt>deviceEvent</dt><dd>Type: <a href="T_DevCase_Core_IO_DeviceEvent">DevCase.Core.IO.DeviceEvent</a><br />The device event.</dd><dt>mouseButton</dt><dd>Type: System.Windows.Forms.MouseButtons<br />\[Missing <param name="mouseButton"/> documentation for "M:DevCase.Core.IO.Eventing.MouseButtonDoubleClickEventArgs.#ctor(DevCase.Core.IO.MouseDeviceInfo,DevCase.Core.IO.DeviceEvent,System.Windows.Forms.MouseButtons)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_MouseButtonDoubleClickEventArgs">MouseButtonDoubleClickEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />