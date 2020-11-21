# MouseInput.MouseData Field
 

If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Flags">Flags</a> contains <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">Wheel</a>, then MouseData specifies the amount of wheel movement. 

 A positive value indicates that the wheel was rotated forward, away from the user. 

 a negative value indicates that the wheel was rotated backward, toward the user. One wheel click is defined as `WHEEL_DELTA`, which is `120`. If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Flags">Flags</a> does not contain <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">Wheel</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">XDown</a>, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">XUp</a>, then MouseData should be `0`.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int MouseData
```

**VB**<br />
``` VB
Public MouseData As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseInput
Dim value As Integer

value = instance.MouseData

instance.MouseData = value
```

**C++**<br />
``` C++
public:
int MouseData
```

**F#**<br />
``` F#
val mutable MouseData: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput">MouseInput Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />