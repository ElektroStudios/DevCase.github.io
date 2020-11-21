# DiskStress.InstanceReadBytes Property 
 

Gets the amount of data read by this instance through I/O read operations.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long InstanceReadBytes { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property InstanceReadBytes As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DiskStress
Dim value As Long

value = instance.InstanceReadBytes

```

**C++**<br />
``` C++
public:
property long long InstanceReadBytes {
	long long get ();
}
```

**F#**<br />
``` F#
member InstanceReadBytes : int64 with get

```


#### Property Value
Type: Int64<br />The amount of data read by this instance through I/O read operations.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DiskStress">DiskStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />