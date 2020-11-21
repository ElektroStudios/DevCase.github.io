# SharedMemoryUtil.ReadString Method (MemoryMappedFile, Int64, Int64, Encoding)
 

Reads a byte sequence from a start position to an end position of an existing MemoryMappedFile, decodes the byte data using the specified Encoding and returns the corresponding string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ReadString(
	MemoryMappedFile mmf,
	long startIndex,
	long endIndex,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function ReadString ( 
	mmf As MemoryMappedFile,
	startIndex As Long,
	endIndex As Long,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFile
Dim startIndex As Long
Dim endIndex As Long
Dim enc As Encoding
Dim returnValue As String

returnValue = SharedMemoryUtil.ReadString(mmf, 
	startIndex, endIndex, enc)
```

**C++**<br />
``` C++
public:
static String^ ReadString(
	MemoryMappedFile^ mmf, 
	long long startIndex, 
	long long endIndex, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member ReadString : 
        mmf : MemoryMappedFile * 
        startIndex : int64 * 
        endIndex : int64 * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd><dt>startIndex</dt><dd>Type: System.Int64<br />The start position to start reading from the MemoryMappedFile segment.</dd><dt>endIndex</dt><dd>Type: System.Int64<br />The end position to stop reading from the MemoryMappedFile segment.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

#### Return Value
Type: String<br />The decoded string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim enc As Encoding = Encoding.Default
Dim str As String = "Hello World!"
Dim result As String

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Write(mmf, enc.GetBytes(str))
    result = SharedMemoryUtil.ReadString(mmf, startIndex:=0, endIndex:=5)

End Using

MessageBox.Show(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_ReadString">ReadString Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />