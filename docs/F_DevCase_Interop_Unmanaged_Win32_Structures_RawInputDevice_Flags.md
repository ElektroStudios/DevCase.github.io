# RawInputDevice.Flags Field
 

Mode flag that specifies how to interpret the information provided by <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_UsagePage">UsagePage</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_Usage">Usage</a>. 

 It can be zero (the default) or one of the following values. 

 By default, the operating system sends raw input from devices with the specified top level collection (TLC) to the registered application as long as it has the window focus.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public RawInputDeviceFlags Flags
```

**VB**<br />
``` VB
Public Flags As RawInputDeviceFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As RawInputDevice
Dim value As RawInputDeviceFlags

value = instance.Flags

instance.Flags = value
```

**C++**<br />
``` C++
public:
RawInputDeviceFlags Flags
```

**F#**<br />
``` F#
val mutable Flags: RawInputDeviceFlags
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RawInputDeviceFlags">RawInputDeviceFlags</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />