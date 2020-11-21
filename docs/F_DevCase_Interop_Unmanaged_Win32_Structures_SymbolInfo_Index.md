# SymbolInfo.Index Field
 

The unique value for the symbol. 

 The value associated with a symbol is not guaranteed to be the same each time you run the process. 

 For `.pbd` symbols, the index value for a symbol is not generated until the symbol is enumerated or retrieved through a search by name or address. 

 The index values for all CodeView and `COFF` symbols are generated when the symbols are loaded.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint Index
```

**VB**<br />
``` VB
Public Index As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As SymbolInfo
Dim value As UInteger

value = instance.Index

instance.Index = value
```

**C++**<br />
``` C++
public:
unsigned int Index
```

**F#**<br />
``` F#
val mutable Index: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo">SymbolInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />