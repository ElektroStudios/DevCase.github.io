# ReparseDataBuffer.PrintNameOffset Field
 

The offset, in bytes, from the beginning of the PathBuffer field, at which the print name is located. 

 The print name is the user-friendly name the client MUST return to the application if it requests the name of the symbolic link target

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ushort PrintNameOffset
```

**VB**<br />
``` VB
Public PrintNameOffset As UShort
```

**VB Usage**<br />
``` VB Usage
Dim instance As ReparseDataBuffer
Dim value As UShort

value = instance.PrintNameOffset

instance.PrintNameOffset = value
```

**C++**<br />
``` C++
public:
unsigned short PrintNameOffset
```

**F#**<br />
``` F#
val mutable PrintNameOffset: uint16
```


#### Field Value
Type: UInt16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer">ReparseDataBuffer Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />