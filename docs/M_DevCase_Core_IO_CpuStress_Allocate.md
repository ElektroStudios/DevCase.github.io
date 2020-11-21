# CpuStress.Allocate Method 
 

Allocates the specified average percentage of CPU usage for this instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Allocate(
	float percentage
)
```

**VB**<br />
``` VB
Public Overridable Sub Allocate ( 
	percentage As Single
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As CpuStress
Dim percentage As Single

instance.Allocate(percentage)
```

**C++**<br />
``` C++
public:
virtual void Allocate(
	float percentage
)
```

**F#**<br />
``` F#
abstract Allocate : 
        percentage : float32 -> unit 
override Allocate : 
        percentage : float32 -> unit 
```


#### Parameters
&nbsp;<dl><dt>percentage</dt><dd>Type: System.Single<br />The average percentage of CPU usage to allocate, from 0.01% to 100%.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Value greater than 0 is required.</td></tr><tr><td>ArgumentOutOfRangeException</td><td>Value must be in range of 0.01% to 100%.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_CpuStress">CpuStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />