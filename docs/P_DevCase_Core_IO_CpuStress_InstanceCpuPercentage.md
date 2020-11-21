# CpuStress.InstanceCpuPercentage Property 
 

Gets the average percentage of CPU usage that is allocated by this instance. 

 Value is in range of 0.01% to 100%.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public float InstanceCpuPercentage { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property InstanceCpuPercentage As Single
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CpuStress
Dim value As Single

value = instance.InstanceCpuPercentage

```

**C++**<br />
``` C++
public:
property float InstanceCpuPercentage {
	float get ();
}
```

**F#**<br />
``` F#
member InstanceCpuPercentage : float32 with get

```


#### Property Value
Type: Single<br />The average percentage of CPU usage that is allocated by this instance.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_CpuStress">CpuStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />