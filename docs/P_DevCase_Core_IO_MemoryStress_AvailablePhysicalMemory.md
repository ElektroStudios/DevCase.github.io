# MemoryStress.AvailablePhysicalMemory Property 
 

Gets the total amount of free physical memory for the computer, in bytes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static long AvailablePhysicalMemory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property AvailablePhysicalMemory As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Long

value = MemoryStress.AvailablePhysicalMemory

```

**C++**<br />
``` C++
public:
static property long long AvailablePhysicalMemory {
	long long get ();
}
```

**F#**<br />
``` F#
static member AvailablePhysicalMemory : int64 with get

```


#### Property Value
Type: Int64<br />The total amount of free physical memory for the computer, in bytes.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MemoryStress">MemoryStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />