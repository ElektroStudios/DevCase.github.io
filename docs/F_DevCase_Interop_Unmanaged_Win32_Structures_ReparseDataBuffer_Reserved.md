# ReparseDataBuffer.Reserved Field
 

Length, in bytes, of the unparsed portion of the file name pointed to by the FileName member of the associated file object. 

 This member is only valid for create operations when the I/O fails with STATUS_REPARSE. For all other purposes, such as setting or querying a reparse point for the reparse data, this member is treated as reserved.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ushort Reserved
```

**VB**<br />
``` VB
Public Reserved As UShort
```

**VB Usage**<br />
``` VB Usage
Dim instance As ReparseDataBuffer
Dim value As UShort

value = instance.Reserved

instance.Reserved = value
```

**C++**<br />
``` C++
public:
unsigned short Reserved
```

**F#**<br />
``` F#
val mutable Reserved: uint16
```


#### Field Value
Type: UInt16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer">ReparseDataBuffer Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />