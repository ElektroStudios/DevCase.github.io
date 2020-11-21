# SharedMemoryUtil.Clear Method (String)
 

Clears the data of an existing MemoryMappedFile segment.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Clear(
	string name
)
```

**VB**<br />
``` VB
Public Shared Sub Clear ( 
	name As String
)
```

**VB Usage**<br />
``` VB Usage
Dim name As StringSharedMemoryUtil.Clear(name)
```

**C++**<br />
``` C++
public:
static void Clear(
	String^ name
)
```

**F#**<br />
``` F#
static member Clear : 
        name : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the MemoryMappedFile segment.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Clear("My MemoryMappedFile Name")

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_Clear">Clear Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />