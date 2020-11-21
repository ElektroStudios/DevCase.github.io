# DiskStress.InstanceReadCount Property 
 

Gets the amount of I/O read operations performed by this instance. This value equals to the amount of files read.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long InstanceReadCount { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property InstanceReadCount As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DiskStress
Dim value As Long

value = instance.InstanceReadCount

```

**C++**<br />
``` C++
public:
property long long InstanceReadCount {
	long long get ();
}
```

**F#**<br />
``` F#
member InstanceReadCount : int64 with get

```


#### Property Value
Type: Int64<br />The amount of I/O read operations performed by this instance.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DiskStress">DiskStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />