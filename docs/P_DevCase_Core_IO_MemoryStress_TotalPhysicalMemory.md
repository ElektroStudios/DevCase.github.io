# MemoryStress.TotalPhysicalMemory Property 
 

Gets the total amount of physical memory for the computer, in bytes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static long TotalPhysicalMemory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property TotalPhysicalMemory As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Long

value = MemoryStress.TotalPhysicalMemory

```

**C++**<br />
``` C++
public:
static property long long TotalPhysicalMemory {
	long long get ();
}
```

**F#**<br />
``` F#
static member TotalPhysicalMemory : int64 with get

```


#### Property Value
Type: Int64<br />The total amount of physical memory for the computer, in bytes.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MemoryStress">MemoryStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />