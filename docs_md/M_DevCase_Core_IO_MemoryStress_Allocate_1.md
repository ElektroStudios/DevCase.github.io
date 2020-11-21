# MemoryStress.Allocate Method (Int64, Byte)
 

Allocates the specified amount of physical memory for this instance and fills the memory with the specified value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SecurityCriticalAttribute]
public virtual void Allocate(
	long size,
	byte fillValue
)
```

**VB**<br />
``` VB
<SecurityCriticalAttribute>
Public Overridable Sub Allocate ( 
	size As Long,
	fillValue As Byte
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryStress
Dim size As Long
Dim fillValue As Byte

instance.Allocate(size, fillValue)
```

**C++**<br />
``` C++
public:
[SecurityCriticalAttribute]
virtual void Allocate(
	long long size, 
	unsigned char fillValue
)
```

**F#**<br />
``` F#
[<SecurityCriticalAttribute>]
abstract Allocate : 
        size : int64 * 
        fillValue : byte -> unit 
[<SecurityCriticalAttribute>]
override Allocate : 
        size : int64 * 
        fillValue : byte -> unit 
```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Int64<br />The amount of physical memory to allocate, in bytes.</dd><dt>fillValue</dt><dd>Type: System.Byte<br />The value that will be used to fill the memory.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Value greater than 0 is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MemoryStress">MemoryStress Class</a><br /><a href="Overload_DevCase_Core_IO_MemoryStress_Allocate">Allocate Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />