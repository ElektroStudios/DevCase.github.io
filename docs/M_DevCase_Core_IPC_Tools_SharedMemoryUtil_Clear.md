# SharedMemoryUtil.Clear Method (MemoryMappedFile)
 

Clears the data of an existing MemoryMappedFile segment.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Clear(
	MemoryMappedFile mmf
)
```

**VB**<br />
``` VB
Public Shared Sub Clear ( 
	mmf As MemoryMappedFile
)
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFileSharedMemoryUtil.Clear(mmf)
```

**C++**<br />
``` C++
public:
static void Clear(
	MemoryMappedFile^ mmf
)
```

**F#**<br />
``` F#
static member Clear : 
        mmf : MemoryMappedFile -> unit 

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Clear(mmf)

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_Clear">Clear Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />