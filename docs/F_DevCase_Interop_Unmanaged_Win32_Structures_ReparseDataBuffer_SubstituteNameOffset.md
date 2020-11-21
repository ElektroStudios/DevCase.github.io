# ReparseDataBuffer.SubstituteNameOffset Field
 

The offset, in bytes, from the beginning of the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Buffer">Buffer</a> member, at which the substitute name is located. 

 The substitute name is the name the client MUST use to access this file if it requires to follow the symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ushort SubstituteNameOffset
```

**VB**<br />
``` VB
Public SubstituteNameOffset As UShort
```

**VB Usage**<br />
``` VB Usage
Dim instance As ReparseDataBuffer
Dim value As UShort

value = instance.SubstituteNameOffset

instance.SubstituteNameOffset = value
```

**C++**<br />
``` C++
public:
unsigned short SubstituteNameOffset
```

**F#**<br />
``` F#
val mutable SubstituteNameOffset: uint16
```


#### Field Value
Type: UInt16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer">ReparseDataBuffer Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />