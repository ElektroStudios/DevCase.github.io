# SharedMemoryUtil.ReadAt Method (MemoryMappedFile, Int64)
 

Reads a byte from a position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte ReadAt(
	MemoryMappedFile mmf,
	long offset
)
```

**VB**<br />
``` VB
Public Shared Function ReadAt ( 
	mmf As MemoryMappedFile,
	offset As Long
) As Byte
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFile
Dim offset As Long
Dim returnValue As Byte

returnValue = SharedMemoryUtil.ReadAt(mmf, offset)
```

**C++**<br />
``` C++
public:
static unsigned char ReadAt(
	MemoryMappedFile^ mmf, 
	long long offset
)
```

**F#**<br />
``` F#
static member ReadAt : 
        mmf : MemoryMappedFile * 
        offset : int64 -> byte 

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd><dt>offset</dt><dd>Type: System.Int64<br />\[Missing <param name="offset"/> documentation for "M:DevCase.Core.IPC.Tools.SharedMemoryUtil.ReadAt(System.IO.MemoryMappedFiles.MemoryMappedFile,System.Int64)"\]</dd></dl>

#### Return Value
Type: Byte<br />The byte value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World!"
Dim result As String

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Write(mmf, Encoding.Default.GetBytes(str))
    result = Convert.ToChar(SharedMemoryUtil.ReadAt(mmf, offset:=0))

End Using

MessageBox.Show(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_ReadAt">ReadAt Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />