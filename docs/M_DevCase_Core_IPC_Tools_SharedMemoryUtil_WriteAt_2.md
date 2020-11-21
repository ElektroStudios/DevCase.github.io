# SharedMemoryUtil.WriteAt Method (String, Byte, Int64)
 

Writes a single byte at the specified position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteAt(
	string name,
	byte value,
	long offset
)
```

**VB**<br />
``` VB
Public Shared Sub WriteAt ( 
	name As String,
	value As Byte,
	offset As Long
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim value As Byte
Dim offset As Long

SharedMemoryUtil.WriteAt(name, value, offset)
```

**C++**<br />
``` C++
public:
static void WriteAt(
	String^ name, 
	unsigned char value, 
	long long offset
)
```

**F#**<br />
``` F#
static member WriteAt : 
        name : string * 
        value : byte * 
        offset : int64 -> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the MemoryMappedFile segment.</dd><dt>value</dt><dd>Type: System.Byte<br />The byte value to write in the MemoryMappedFile segment.</dd><dt>offset</dt><dd>Type: System.Int64<br />The position in the MemoryMappedFile segment to start writing from.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.WriteAt("My MemoryMappedFile Name", New Byte, offset:=0)

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_WriteAt">WriteAt Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />