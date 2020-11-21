# SharedMemoryUtil.WriteCharAt Method (MemoryMappedFile, Char, Int64, Encoding)
 

Writes a character at the specified position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteCharAt(
	MemoryMappedFile mmf,
	char c,
	long offset,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub WriteCharAt ( 
	mmf As MemoryMappedFile,
	c As Char,
	offset As Long,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFile
Dim c As Char
Dim offset As Long
Dim enc As EncodingSharedMemoryUtil.WriteCharAt(mmf, c, offset, enc)
```

**C++**<br />
``` C++
public:
static void WriteCharAt(
	MemoryMappedFile^ mmf, 
	wchar_t c, 
	long long offset, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member WriteCharAt : 
        mmf : MemoryMappedFile * 
        c : char * 
        offset : int64 * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd><dt>c</dt><dd>Type: System.Char<br />The character to write in the MemoryMappedFile segment.</dd><dt>offset</dt><dd>Type: System.Int64<br />The position in the MemoryMappedFile segment to start writing from.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The character Encoding.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.WriteCharAt(mmf, "A"c, offset:=0, encoding:=Encoding.Default)

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_WriteCharAt">WriteCharAt Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />