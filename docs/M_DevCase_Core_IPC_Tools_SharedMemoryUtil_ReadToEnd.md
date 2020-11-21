# SharedMemoryUtil.ReadToEnd Method (MemoryMappedFile)
 

Reads from start to end the data of an existing MemoryMappedFile. Note that the returned bytes could contain null bytes at the end due to the automatic size rounding of a multiple of 4096 bytes (4 KB).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] ReadToEnd(
	MemoryMappedFile mmf
)
```

**VB**<br />
``` VB
Public Shared Function ReadToEnd ( 
	mmf As MemoryMappedFile
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFile
Dim returnValue As Byte()

returnValue = SharedMemoryUtil.ReadToEnd(mmf)
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ ReadToEnd(
	MemoryMappedFile^ mmf
)
```

**F#**<br />
``` F#
static member ReadToEnd : 
        mmf : MemoryMappedFile -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd></dl>

#### Return Value
Type: Byte[]<br />The byte-data.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim enc As Encoding = Encoding.Default
Dim str As String = "Hello World!"
Dim result As String

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Write(mmf, enc.GetBytes(str))
    result = enc.GetString(SharedMemoryUtil.ReadToEnd(mmf)).TrimEnd(ControlChars.NullChar)

End Using

MessageBox.Show(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_ReadToEnd">ReadToEnd Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />