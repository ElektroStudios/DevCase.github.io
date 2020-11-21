# SharedMemoryUtil.Write(*T*) Method (MemoryMappedFile, *T*)
 

Writes a structure at the start position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Write<T>(
	MemoryMappedFile mmf,
	ref T refStructure
)
where T : struct, new()

```

**VB**<br />
``` VB
Public Shared Sub Write(Of T As {Structure, New}) ( 
	mmf As MemoryMappedFile,
	ByRef refStructure As T
)
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFile
Dim refStructure As T

SharedMemoryUtil.Write(mmf, refStructure)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : value class, gcnew()
static void Write(
	MemoryMappedFile^ mmf, 
	T% refStructure
)
```

**F#**<br />
``` F#
static member Write : 
        mmf : MemoryMappedFile * 
        refStructure : 'T byref -> unit  when 'T : struct, new()

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd><dt>refStructure</dt><dd>Type: *T*<br />The structure to write.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of strucure.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myStructure as Color = Color.Red

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)
    SharedMemoryUtil.Write(Of Color)(mmf, myStructure)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_Write">Write Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />