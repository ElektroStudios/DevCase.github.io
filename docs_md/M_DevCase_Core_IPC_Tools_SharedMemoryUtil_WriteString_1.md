# SharedMemoryUtil.WriteString Method (String, String, Encoding)
 

Writes a String at the start position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteString(
	string name,
	string str,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub WriteString ( 
	name As String,
	str As String,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim str As String
Dim enc As EncodingSharedMemoryUtil.WriteString(name, str, enc)
```

**C++**<br />
``` C++
public:
static void WriteString(
	String^ name, 
	String^ str, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member WriteString : 
        name : string * 
        str : string * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the MemoryMappedFile segment.</dd><dt>str</dt><dd>Type: System.String<br />The text to write in the MemoryMappedFile segment.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.WriteString("My MemoryMappedFile Name", "Hello World!", Encoding.Default)

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_WriteString">WriteString Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />