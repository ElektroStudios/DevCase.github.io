# SymbolInfo.SizeOfStruct Field
 

The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of SymbolInfo)` before calling any function. 

 Note that the total size of the data is the `SizeOfStruct + (MaxNameLen - 1) * Marshal.SizeOf(Char)`. 

 The reason to subtract one is that the first character in the name is accounted for in the size of the structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint SizeOfStruct
```

**VB**<br />
``` VB
Public SizeOfStruct As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As SymbolInfo
Dim value As UInteger

value = instance.SizeOfStruct

instance.SizeOfStruct = value
```

**C++**<br />
``` C++
public:
unsigned int SizeOfStruct
```

**F#**<br />
``` F#
val mutable SizeOfStruct: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo">SymbolInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />