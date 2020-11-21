# MemoryStatusEx.PageFileTotal Field
 

Size of the committed memory limit, in bytes. 

 This is physical memory plus the size of the page file, minus a small overhead.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ulong PageFileTotal
```

**VB**<br />
``` VB
Public PageFileTotal As ULong
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryStatusEx
Dim value As ULong

value = instance.PageFileTotal

instance.PageFileTotal = value
```

**C++**<br />
``` C++
public:
unsigned long long PageFileTotal
```

**F#**<br />
``` F#
val mutable PageFileTotal: uint64
```


#### Field Value
Type: UInt64

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx">MemoryStatusEx Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />