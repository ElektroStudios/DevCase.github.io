# SharedMemoryUtil.Write Method (MemoryMappedFile, Byte[])
 

Writes a byte sequence at the start position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Write(
	MemoryMappedFile mmf,
	byte[] data
)
```

**VB**<br />
``` VB
Public Shared Sub Write ( 
	mmf As MemoryMappedFile,
	data As Byte()
)
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFile
Dim data As Byte()

SharedMemoryUtil.Write(mmf, data)
```

**C++**<br />
``` C++
public:
static void Write(
	MemoryMappedFile^ mmf, 
	array<unsigned char>^ data
)
```

**F#**<br />
``` F#
static member Write : 
        mmf : MemoryMappedFile * 
        data : byte[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd><dt>data</dt><dd>Type: System.Byte[]<br />The byte sequence to write in the MemoryMappedFile segment.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Write(mmf, Encoding.Default.GetBytes("Hello World!"))

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_Write">Write Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />