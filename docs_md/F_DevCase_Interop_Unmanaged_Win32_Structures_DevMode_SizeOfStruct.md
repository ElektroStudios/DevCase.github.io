# DevMode.SizeOfStruct Field
 

Specifies the size, in bytes, of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode</a> structure, not including any private driver-specific data that might follow the structure's public members. 

 This member must be set to `Marshal.SizeOf(Of DevMode)` before calling any function, to indicate the version of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode</a> structure being used.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public short SizeOfStruct
```

**VB**<br />
``` VB
Public SizeOfStruct As Short
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As Short

value = instance.SizeOfStruct

instance.SizeOfStruct = value
```

**C++**<br />
``` C++
public:
short SizeOfStruct
```

**F#**<br />
``` F#
val mutable SizeOfStruct: int16
```


#### Field Value
Type: Int16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />