# ReparseDataBuffer.Buffer Field
 

A buffer that contains the Unicode strings for the substitute name and the print name, as described by <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameOffset">SubstituteNameOffset</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameLength">SubstituteNameLength</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameOffset">PrintNameOffset</a>, and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameLength">PrintNameLength</a>. 

 The substitute name string MUST be a Unicode path to the target of the symbolic link. 

 The print name string MUST be a Unicode string, suitable for display to a user, that also identifies the target of the symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public byte[] Buffer
```

**VB**<br />
``` VB
Public Buffer As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim instance As ReparseDataBuffer
Dim value As Byte()

value = instance.Buffer

instance.Buffer = value
```

**C++**<br />
``` C++
public:
array<unsigned char>^ Buffer
```

**F#**<br />
``` F#
val mutable Buffer: byte[]
```


#### Field Value
Type: Byte[]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer">ReparseDataBuffer Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />