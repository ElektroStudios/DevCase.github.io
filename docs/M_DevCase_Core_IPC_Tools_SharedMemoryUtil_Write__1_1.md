# SharedMemoryUtil.Write(*T*) Method (String, *T*)
 

Writes a structure at the start position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Write<T>(
	string name,
	ref T refStructure
)
where T : struct, new()

```

**VB**<br />
``` VB
Public Shared Sub Write(Of T As {Structure, New}) ( 
	name As String,
	ByRef refStructure As T
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim refStructure As T

SharedMemoryUtil.Write(name, refStructure)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : value class, gcnew()
static void Write(
	String^ name, 
	T% refStructure
)
```

**F#**<br />
``` F#
static member Write : 
        name : string * 
        refStructure : 'T byref -> unit  when 'T : struct, new()

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the MemoryMappedFile segment.</dd><dt>refStructure</dt><dd>Type: *T*<br />The structure to write.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of strucure.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myStructure as Color = Color.Red

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)
    SharedMemoryUtil.Write(Of Color)("My MemoryMappedFile Name", myStructure)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_Write">Write Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />