# SharedMemoryUtil.Write Method (String, Byte[])
 

Writes a byte sequence at the start position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Write(
	string name,
	byte[] data
)
```

**VB**<br />
``` VB
Public Shared Sub Write ( 
	name As String,
	data As Byte()
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim data As Byte()

SharedMemoryUtil.Write(name, data)
```

**C++**<br />
``` C++
public:
static void Write(
	String^ name, 
	array<unsigned char>^ data
)
```

**F#**<br />
``` F#
static member Write : 
        name : string * 
        data : byte[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the MemoryMappedFile segment.</dd><dt>data</dt><dd>Type: System.Byte[]<br />The byte sequence to write in the MemoryMappedFile segment.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Write("My MemoryMappedFile Name", Encoding.Default.GetBytes("Hello World!"))

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_Write">Write Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />