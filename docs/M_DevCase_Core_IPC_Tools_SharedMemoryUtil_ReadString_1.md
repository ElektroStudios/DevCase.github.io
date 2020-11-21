# SharedMemoryUtil.ReadString Method (String, Int64, Int64, Encoding)
 

Reads a byte sequence from a start position to an end position of an existing MemoryMappedFile, decodes the byte data using the specified Encoding and returns the corresponding string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ReadString(
	string name,
	long starIndex,
	long endIndex,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function ReadString ( 
	name As String,
	starIndex As Long,
	endIndex As Long,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim starIndex As Long
Dim endIndex As Long
Dim enc As Encoding
Dim returnValue As String

returnValue = SharedMemoryUtil.ReadString(name, 
	starIndex, endIndex, enc)
```

**C++**<br />
``` C++
public:
static String^ ReadString(
	String^ name, 
	long long starIndex, 
	long long endIndex, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member ReadString : 
        name : string * 
        starIndex : int64 * 
        endIndex : int64 * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the MemoryMappedFile segment.</dd><dt>starIndex</dt><dd>Type: System.Int64<br />The start position to start reading from the MemoryMappedFile segment.</dd><dt>endIndex</dt><dd>Type: System.Int64<br />The end position to stop reading from the MemoryMappedFile segment.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

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

    SharedMemoryUtil.Write("My MemoryMappedFile Name", enc.GetBytes(str))
    result = SharedMemoryUtil.ReadString("My MemoryMappedFile Name", startIndex:=0, endIndex:=5)

End Using

MessageBox.Show(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_ReadString">ReadString Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />