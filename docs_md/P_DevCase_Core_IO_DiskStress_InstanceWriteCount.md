# DiskStress.InstanceWriteCount Property 
 

Gets the amount of I/O write operations performed by this instance. This value equals to the amount of files written.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long InstanceWriteCount { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property InstanceWriteCount As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DiskStress
Dim value As Long

value = instance.InstanceWriteCount

```

**C++**<br />
``` C++
public:
property long long InstanceWriteCount {
	long long get ();
}
```

**F#**<br />
``` F#
member InstanceWriteCount : int64 with get

```


#### Property Value
Type: Int64<br />The amount of I/O write operations performed by this instance.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DiskStress">DiskStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />