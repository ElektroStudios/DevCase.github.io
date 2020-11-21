# DiskStress.ProcessWriteCount Property 
 

Gets the amount of I/O write operations performed by the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long ProcessWriteCount { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ProcessWriteCount As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DiskStress
Dim value As Long

value = instance.ProcessWriteCount

```

**C++**<br />
``` C++
public:
property long long ProcessWriteCount {
	long long get ();
}
```

**F#**<br />
``` F#
member ProcessWriteCount : int64 with get

```


#### Property Value
Type: Int64<br />The amount of I/O write operations performed by the current process.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DiskStress">DiskStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />