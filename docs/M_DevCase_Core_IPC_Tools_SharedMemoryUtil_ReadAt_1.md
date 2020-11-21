# SharedMemoryUtil.ReadAt Method (String, Int64)
 

Reads a byte from a position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte ReadAt(
	string name,
	long offset
)
```

**VB**<br />
``` VB
Public Shared Function ReadAt ( 
	name As String,
	offset As Long
) As Byte
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim offset As Long
Dim returnValue As Byte

returnValue = SharedMemoryUtil.ReadAt(name, offset)
```

**C++**<br />
``` C++
public:
static unsigned char ReadAt(
	String^ name, 
	long long offset
)
```

**F#**<br />
``` F#
static member ReadAt : 
        name : string * 
        offset : int64 -> byte 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the MemoryMappedFile segment.</dd><dt>offset</dt><dd>Type: System.Int64<br />\[Missing <param name="offset"/> documentation for "M:DevCase.Core.IPC.Tools.SharedMemoryUtil.ReadAt(System.String,System.Int64)"\]</dd></dl>

#### Return Value
Type: Byte<br />The byte value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World!"
Dim result As String

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Write("My MemoryMappedFile Name", Encoding.Default.GetBytes(str))
    result = Convert.ToChar(SharedMemoryUtil.ReadAt("My MemoryMappedFile Name", offset:=0))

End Using

MessageBox.Show(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_ReadAt">ReadAt Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />