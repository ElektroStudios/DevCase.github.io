# HotkeyPastePressedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Eventing_HotkeyPastePressedEventArgs">HotkeyPastePressedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public HotkeyPastePressedEventArgs(
	KeyboardDeviceInfo deviceInfo,
	string clipboardData
)
```

**VB**<br />
``` VB
Public Sub New ( 
	deviceInfo As KeyboardDeviceInfo,
	clipboardData As String
)
```

**VB Usage**<br />
``` VB Usage
Dim deviceInfo As KeyboardDeviceInfo
Dim clipboardData As String

Dim instance As New HotkeyPastePressedEventArgs(deviceInfo, 
	clipboardData)
```

**C++**<br />
``` C++
public:
HotkeyPastePressedEventArgs(
	KeyboardDeviceInfo^ deviceInfo, 
	String^ clipboardData
)
```

**F#**<br />
``` F#
new : 
        deviceInfo : KeyboardDeviceInfo * 
        clipboardData : string -> HotkeyPastePressedEventArgs
```


#### Parameters
&nbsp;<dl><dt>deviceInfo</dt><dd>Type: <a href="T_DevCase_Core_IO_KeyboardDeviceInfo">DevCase.Core.IO.KeyboardDeviceInfo</a><br />The device data.</dd><dt>clipboardData</dt><dd>Type: System.String<br />The clipboard data.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_HotkeyPastePressedEventArgs">HotkeyPastePressedEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />