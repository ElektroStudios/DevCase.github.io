# MouseInput.Flags Field
 

A set of bit flags that specify various aspects of mouse motion and button clicks. 

 The bit flags that specify mouse button status are set to indicate changes in status, not ongoing conditions. 

 For example, if the left mouse button is pressed and held down, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">LeftDown</a> is set when the left button is first pressed, but not for subsequent motions. 

 Similarly, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">LeftUp</a> is set only when the button is first released. 

 You cannot specify both the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">Wheel</a> flag and either <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">XDown</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">XUp</a> flags simultaneously in the Flags parameter, because they both require use of the 'mouseData' field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MouseInputFlags Flags
```

**VB**<br />
``` VB
Public Flags As MouseInputFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseInput
Dim value As MouseInputFlags

value = instance.Flags

instance.Flags = value
```

**C++**<br />
``` C++
public:
MouseInputFlags Flags
```

**F#**<br />
``` F#
val mutable Flags: MouseInputFlags
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">MouseInputFlags</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput">MouseInput Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />