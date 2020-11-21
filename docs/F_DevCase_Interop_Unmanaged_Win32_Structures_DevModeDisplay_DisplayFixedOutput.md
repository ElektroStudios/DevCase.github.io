# DevModeDisplay.DisplayFixedOutput Field
 

For fixed-resolution display devices only, how the display presents a low-resolution mode on a higher-resolution display. 

 For example, if a display device's resolution is fixed at 1024 x 768 pixels but its mode is set to 640x480 pixels, the device can either display a 640x480 image somewhere in the interior of the 1024x768 screen space or stretch the 640x480 image to fill the larger screen space. 

 If <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeFields">DisplayFixedOutput</a> is not set, this member must be zero.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int DisplayFixedOutput
```

**VB**<br />
``` VB
Public DisplayFixedOutput As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevModeDisplay
Dim value As Integer

value = instance.DisplayFixedOutput

instance.DisplayFixedOutput = value
```

**C++**<br />
``` C++
public:
int DisplayFixedOutput
```

**F#**<br />
``` F#
val mutable DisplayFixedOutput: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevModeDisplay">DevModeDisplay Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />