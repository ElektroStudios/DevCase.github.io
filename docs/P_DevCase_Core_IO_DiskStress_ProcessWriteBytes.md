# DiskStress.ProcessWriteBytes Property 
 

Gets the amount of data written by the current process through I/O write operations.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long ProcessWriteBytes { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ProcessWriteBytes As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DiskStress
Dim value As Long

value = instance.ProcessWriteBytes

```

**C++**<br />
``` C++
public:
property long long ProcessWriteBytes {
	long long get ();
}
```

**F#**<br />
``` F#
member ProcessWriteBytes : int64 with get

```


#### Property Value
Type: Int64<br />The amount of data written by the current process through I/O write operations.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DiskStress">DiskStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />