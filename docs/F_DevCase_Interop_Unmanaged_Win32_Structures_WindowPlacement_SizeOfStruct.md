# WindowPlacement.SizeOfStruct Field
 

The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of WindowPlacement)` before calling any function. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowPlacement">GetWindowPlacement(IntPtr, WindowPlacement)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowPlacement">SetWindowPlacement(IntPtr, WindowPlacement)</a> fail if this member is not set correctly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int SizeOfStruct
```

**VB**<br />
``` VB
Public SizeOfStruct As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowPlacement
Dim value As Integer

value = instance.SizeOfStruct

instance.SizeOfStruct = value
```

**C++**<br />
``` C++
public:
int SizeOfStruct
```

**F#**<br />
``` F#
val mutable SizeOfStruct: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement">WindowPlacement Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />