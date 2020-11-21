# CpuStress.ProcessCpuPercentage Property 
 

Gets the average percentage of CPU usage that is allocated by the current process. 

 Value is in range of 0% to 100%.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public float ProcessCpuPercentage { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ProcessCpuPercentage As Single
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CpuStress
Dim value As Single

value = instance.ProcessCpuPercentage

```

**C++**<br />
``` C++
public:
property float ProcessCpuPercentage {
	float get ();
}
```

**F#**<br />
``` F#
member ProcessCpuPercentage : float32 with get

```


#### Property Value
Type: Single<br />The average percentage of CPU usage that is allocated by the current process.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_CpuStress">CpuStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />