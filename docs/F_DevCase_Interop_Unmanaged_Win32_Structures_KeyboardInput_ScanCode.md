# KeyboardInput.ScanCode Field
 

A hardware scan code for the key. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeyboardInputFlags">Unicode</a>, ScanCode specifies a Unicode character which is to be sent to the foreground application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public short ScanCode
```

**VB**<br />
``` VB
Public ScanCode As Short
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardInput
Dim value As Short

value = instance.ScanCode

instance.ScanCode = value
```

**C++**<br />
``` C++
public:
short ScanCode
```

**F#**<br />
``` F#
val mutable ScanCode: int16
```


#### Field Value
Type: Int16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput">KeyboardInput Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />