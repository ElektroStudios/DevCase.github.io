# ReparseDataBuffer.SubstituteNameLength Field
 

The length, in bytes, of the substitute name string. 

 If there is a terminating null character at the end of the string, it is not included in the SubstituteNameLength count. 

 This value MUST be greater than or equal to 0.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ushort SubstituteNameLength
```

**VB**<br />
``` VB
Public SubstituteNameLength As UShort
```

**VB Usage**<br />
``` VB Usage
Dim instance As ReparseDataBuffer
Dim value As UShort

value = instance.SubstituteNameLength

instance.SubstituteNameLength = value
```

**C++**<br />
``` C++
public:
unsigned short SubstituteNameLength
```

**F#**<br />
``` F#
val mutable SubstituteNameLength: uint16
```


#### Field Value
Type: UInt16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer">ReparseDataBuffer Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />