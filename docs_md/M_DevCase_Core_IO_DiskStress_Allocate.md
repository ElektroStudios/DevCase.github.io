# DiskStress.Allocate Method 
 

Starts allocating I/O read and write operations for the current process running this instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Allocate(
	int fileSize = 1048576
)
```

**VB**<br />
``` VB
Public Overridable Sub Allocate ( 
	Optional fileSize As Integer = 1048576
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DiskStress
Dim fileSize As Integer

instance.Allocate(fileSize)
```

**C++**<br />
``` C++
public:
virtual void Allocate(
	int fileSize = 1048576
)
```

**F#**<br />
``` F#
abstract Allocate : 
        ?fileSize : int 
(* Defaults:
        let _fileSize = defaultArg fileSize 1048576
*)
-> unit 
override Allocate : 
        ?fileSize : int 
(* Defaults:
        let _fileSize = defaultArg fileSize 1048576
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>fileSize (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="fileSize"/> documentation for "M:DevCase.Core.IO.DiskStress.Allocate(System.Int32)"\]</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Value greater than 0 is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DiskStress">DiskStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />