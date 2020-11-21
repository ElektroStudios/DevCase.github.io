# SharedMemoryUtil.Create Method 
 

Creates a MemoryMappedFile segment that is shared between applications.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static MemoryMappedFile Create(
	string name,
	int capacity,
	MemoryMappedFileAccess fileAccess = MemoryMappedFileAccess.ReadWrite
)
```

**VB**<br />
``` VB
Public Shared Function Create ( 
	name As String,
	capacity As Integer,
	Optional fileAccess As MemoryMappedFileAccess = MemoryMappedFileAccess.ReadWrite
) As MemoryMappedFile
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim capacity As Integer
Dim fileAccess As MemoryMappedFileAccess
Dim returnValue As MemoryMappedFile

returnValue = SharedMemoryUtil.Create(name, capacity, 
	fileAccess)
```

**C++**<br />
``` C++
public:
static MemoryMappedFile^ Create(
	String^ name, 
	int capacity, 
	MemoryMappedFileAccess fileAccess = MemoryMappedFileAccess::ReadWrite
)
```

**F#**<br />
``` F#
static member Create : 
        name : string * 
        capacity : int * 
        ?fileAccess : MemoryMappedFileAccess 
(* Defaults:
        let _fileAccess = defaultArg fileAccess MemoryMappedFileAccess.ReadWrite
*)
-> MemoryMappedFile 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name to assign the MemoryMappedFile segment.</dd><dt>capacity</dt><dd>Type: System.Int32<br />The maximum size, in bytes, to allocate data on the MemoryMappedFile segment. The specified value is automatically rounded to a multiple of 4096 bytes (4 KB), for example a value of 1 will be rounded to 4096, a value of 4097 will be rounded to 8192, and a value of 9999 to 12288.</dd><dt>fileAccess (Optional)</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFileAccess<br />The MemoryMappedFileAccess.</dd></dl>

#### Return Value
Type: MemoryMappedFile<br />\[Missing <returns> documentation for "M:DevCase.Core.IPC.Tools.SharedMemoryUtil.Create(System.String,System.Int32,System.IO.MemoryMappedFiles.MemoryMappedFileAccess)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />