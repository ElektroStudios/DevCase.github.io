# SharedMemoryUtil.Read Method (String, Int64, Int64)
 

Reads a byte sequence from a start position to an end position of an existing MemoryMappedFile. Note that the returned bytes could contain null bytes at the end due to the automatic size rounding of a multiple of 4096 bytes (4 KB).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] Read(
	string name,
	long starIndex,
	long endIndex
)
```

**VB**<br />
``` VB
Public Shared Function Read ( 
	name As String,
	starIndex As Long,
	endIndex As Long
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim starIndex As Long
Dim endIndex As Long
Dim returnValue As Byte()

returnValue = SharedMemoryUtil.Read(name, starIndex, 
	endIndex)
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ Read(
	String^ name, 
	long long starIndex, 
	long long endIndex
)
```

**F#**<br />
``` F#
static member Read : 
        name : string * 
        starIndex : int64 * 
        endIndex : int64 -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name o the MemoryMappedFile segment.</dd><dt>starIndex</dt><dd>Type: System.Int64<br />The start position to start reading from the MemoryMappedFile segment.</dd><dt>endIndex</dt><dd>Type: System.Int64<br />The end position to stop reading from the MemoryMappedFile segment.</dd></dl>

#### Return Value
Type: Byte[]<br />The byte sequence.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim enc As Encoding = Encoding.Default
Dim str As String = "Hello World!"
Dim result As String

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Write("My MemoryMappedFile Name", enc.GetBytes(str))
    result = enc.GetString(SharedMemoryUtil.Read("My MemoryMappedFile Name", starIndex:=0, endIndex:=5))

End Using

MessageBox.Show(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_Read">Read Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />