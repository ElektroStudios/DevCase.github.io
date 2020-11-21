# SharedMemoryUtil.WriteStringAt Method (MemoryMappedFile, String, Int64, Encoding)
 

Writes a String at the specified position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteStringAt(
	MemoryMappedFile mmf,
	string str,
	long offset,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub WriteStringAt ( 
	mmf As MemoryMappedFile,
	str As String,
	offset As Long,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFile
Dim str As String
Dim offset As Long
Dim enc As EncodingSharedMemoryUtil.WriteStringAt(mmf, str, offset, 
	enc)
```

**C++**<br />
``` C++
public:
static void WriteStringAt(
	MemoryMappedFile^ mmf, 
	String^ str, 
	long long offset, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member WriteStringAt : 
        mmf : MemoryMappedFile * 
        str : string * 
        offset : int64 * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd><dt>str</dt><dd>Type: System.String<br />The text to write in the MemoryMappedFile segment.</dd><dt>offset</dt><dd>Type: System.Int64<br />The position in the MemoryMappedFile segment to start writing from.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.WriteStringAt(mmf, "Hello World!", offset:=0, encoding:=Encoding.Default)

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_WriteStringAt">WriteStringAt Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />