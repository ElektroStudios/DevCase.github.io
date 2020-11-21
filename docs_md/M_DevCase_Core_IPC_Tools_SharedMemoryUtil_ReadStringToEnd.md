# SharedMemoryUtil.ReadStringToEnd Method (MemoryMappedFile, Encoding)
 

Reads from start to end the data of an existing MemoryMappedFile, decodes the byte data using the specified Encoding and returns the corresponding string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ReadStringToEnd(
	MemoryMappedFile mmf,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function ReadStringToEnd ( 
	mmf As MemoryMappedFile,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim mmf As MemoryMappedFile
Dim enc As Encoding
Dim returnValue As String

returnValue = SharedMemoryUtil.ReadStringToEnd(mmf, 
	enc)
```

**C++**<br />
``` C++
public:
static String^ ReadStringToEnd(
	MemoryMappedFile^ mmf, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member ReadStringToEnd : 
        mmf : MemoryMappedFile * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>mmf</dt><dd>Type: System.IO.MemoryMappedFiles.MemoryMappedFile<br />The MemoryMappedFile segment.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

#### Return Value
Type: String<br />The byte-data.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim enc As Encoding = Encoding.Default
Dim str As String = "Hello World!"
Dim result As String

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Write(mmf, enc.GetBytes(str))
    result = SharedMemoryUtil.ReadStringToEnd(mmf, enc)

End Using

MessageBox.Show(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_ReadStringToEnd">ReadStringToEnd Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />