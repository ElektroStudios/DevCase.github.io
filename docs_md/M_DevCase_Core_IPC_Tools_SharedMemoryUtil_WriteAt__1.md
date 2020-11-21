# SharedMemoryUtil.WriteAt(*T*) Method (MemoryMappedFile, *T*, Int64)
 

Writes a structure at the specified position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteAt<T>(
	MemoryMappedFile mmf,
	ref T refStructure,
	long offset
)
where T : struct, new()

```

**VB**<br />
``` VB
Public Shared Sub WriteAt(Of T As {Structure, New}) ( 
	mmf As MemoryMappedFile,
	ByRef refStructure As T,
	offset As Long
)
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFile
Dim refStructure As T
Dim offset As Long

SharedMemoryUtil.WriteAt(mmf, refStructure, offset)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : value class, gcnew()
static void WriteAt(
	MemoryMappedFile^ mmf, 
	T% refStructure, 
	long long offset
)
```

**F#**<br />
``` F#
static member WriteAt : 
        mmf : MemoryMappedFile * 
        refStructure : 'T byref * 
        offset : int64 -> unit  when 'T : struct, new()

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd><dt>refStructure</dt><dd>Type: *T*<br />The structure to write.</dd><dt>offset</dt><dd>Type: System.Int64<br />The position in the MemoryMappedFile segment to start writing from.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of strucure.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myStructure as Color = Color.Red

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)
    SharedMemoryUtil.Write(Of Color)(mmf, myStructure, 0L)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_WriteAt">WriteAt Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />