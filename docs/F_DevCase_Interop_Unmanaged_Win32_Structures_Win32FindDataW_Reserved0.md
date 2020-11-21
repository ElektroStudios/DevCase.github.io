# Win32FindDataW.Reserved0 Field
 

If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_FileAttributes">FileAttributes</a> member includes the FILE_ATTRIBUTE_REPARSE_POINT attribute, this member specifies the reparse point tag. Otherwise, this value is undefined and should not be used.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint Reserved0
```

**VB**<br />
``` VB
Public Reserved0 As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As Win32FindDataW
Dim value As UInteger

value = instance.Reserved0

instance.Reserved0 = value
```

**C++**<br />
``` C++
public:
unsigned int Reserved0
```

**F#**<br />
``` F#
val mutable Reserved0: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW">Win32FindDataW Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />