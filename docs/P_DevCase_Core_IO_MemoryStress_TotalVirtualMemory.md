# MemoryStress.TotalVirtualMemory Property 
 

Gets the total amount of virtual address space available for the computer, in bytes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static long TotalVirtualMemory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property TotalVirtualMemory As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Long

value = MemoryStress.TotalVirtualMemory

```

**C++**<br />
``` C++
public:
static property long long TotalVirtualMemory {
	long long get ();
}
```

**F#**<br />
``` F#
static member TotalVirtualMemory : int64 with get

```


#### Property Value
Type: Int64<br />The total amount of virtual address space available for the computer, in bytes.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MemoryStress">MemoryStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />