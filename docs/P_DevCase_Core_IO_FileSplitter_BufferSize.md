# FileSplitter.BufferSize Property 
 

Gets or sets the buffer size used to split or merge, in Bytes. 

 Default value is: <a href="T_DevCase_Core_IO_BufferSizes">Kb128</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public BufferSizes BufferSize { get; set; }
```

**VB**<br />
``` VB
Public Property BufferSize As BufferSizes
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSplitter
Dim value As BufferSizes

value = instance.BufferSize

instance.BufferSize = value
```

**C++**<br />
``` C++
public:
property BufferSizes BufferSize {
	BufferSizes get ();
	void set (BufferSizes value);
}
```

**F#**<br />
``` F#
member BufferSize : BufferSizes with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_IO_BufferSizes">BufferSizes</a><br />The buffer size.

## Remarks
4096 Bytes ( 4 Kb) This is the default buffer size of the Microsoft's FileStream implementation. 8192 Bytes ( 8 Kb) 16384 Bytes ( 16 Kb) 32768 Bytes ( 32 Kb) 65536 Bytes ( 64 Kb) 131072 Bytes (128 Kb) 262144 Bytes (256 Kb) 524288 Bytes (512 Kb) 1048576 Bytes ( 1 Mb)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSplitter">FileSplitter Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />