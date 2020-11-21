# MemoryStress.InstancePhysicalMemorySize Property 
 

Gets the total amount of physical memory, in bytes, that is allocated by this instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long InstancePhysicalMemorySize { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property InstancePhysicalMemorySize As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryStress
Dim value As Long

value = instance.InstancePhysicalMemorySize

```

**C++**<br />
``` C++
public:
property long long InstancePhysicalMemorySize {
	long long get ();
}
```

**F#**<br />
``` F#
member InstancePhysicalMemorySize : int64 with get

```


#### Property Value
Type: Int64<br />The total amount of physical memory, in bytes, that is allocated by this instance.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MemoryStress">MemoryStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />