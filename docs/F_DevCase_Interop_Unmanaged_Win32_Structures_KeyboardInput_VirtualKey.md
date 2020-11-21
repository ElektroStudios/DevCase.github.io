# KeyboardInput.VirtualKey Field
 

A virtual-key code. 

 The code must be a value in the range `1` to `254`. 

 If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Flags">Flags</a> member specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeyboardInputFlags">Unicode</a>, VirtualKey must be `0`.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public short VirtualKey
```

**VB**<br />
``` VB
Public VirtualKey As Short
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardInput
Dim value As Short

value = instance.VirtualKey

instance.VirtualKey = value
```

**C++**<br />
``` C++
public:
short VirtualKey
```

**F#**<br />
``` F#
val mutable VirtualKey: int16
```


#### Field Value
Type: Int16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput">KeyboardInput Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />