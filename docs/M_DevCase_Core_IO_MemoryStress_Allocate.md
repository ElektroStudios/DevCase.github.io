# MemoryStress.Allocate Method (Int64)
 

Allocates the specified amount of physical memory for this instance and fills the memory with zeros.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Allocate(
	long size
)
```

**VB**<br />
``` VB
Public Overridable Sub Allocate ( 
	size As Long
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryStress
Dim size As Long

instance.Allocate(size)
```

**C++**<br />
``` C++
public:
virtual void Allocate(
	long long size
)
```

**F#**<br />
``` F#
abstract Allocate : 
        size : int64 -> unit 
override Allocate : 
        size : int64 -> unit 
```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Int64<br />The amount of physical memory to allocate, in bytes.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Value greater than 0 is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MemoryStress">MemoryStress Class</a><br /><a href="Overload_DevCase_Core_IO_MemoryStress_Allocate">Allocate Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />