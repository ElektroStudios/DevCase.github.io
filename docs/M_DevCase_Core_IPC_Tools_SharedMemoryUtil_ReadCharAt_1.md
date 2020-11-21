# SharedMemoryUtil.ReadCharAt Method (String, Int64)
 

Reads a character from a position of an existing MemoryMappedFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static char ReadCharAt(
	string name,
	long offset
)
```

**VB**<br />
``` VB
Public Shared Function ReadCharAt ( 
	name As String,
	offset As Long
) As Char
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim offset As Long
Dim returnValue As Char

returnValue = SharedMemoryUtil.ReadCharAt(name, 
	offset)
```

**C++**<br />
``` C++
public:
static wchar_t ReadCharAt(
	String^ name, 
	long long offset
)
```

**F#**<br />
``` F#
static member ReadCharAt : 
        name : string * 
        offset : int64 -> char 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the MemoryMappedFile segment.</dd><dt>offset</dt><dd>Type: System.Int64<br />\[Missing <param name="offset"/> documentation for "M:DevCase.Core.IPC.Tools.SharedMemoryUtil.ReadCharAt(System.String,System.Int64)"\]</dd></dl>

#### Return Value
Type: Char<br />The character.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World!"
Dim result As Char

Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    SharedMemoryUtil.Write("My MemoryMappedFile Name", Encoding.Default.GetBytes(str))
    result = SharedMemoryUtil.ReadCharAt("My MemoryMappedFile Name", offset:=0)

End Using

MessageBox.Show(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_SharedMemoryUtil_ReadCharAt">ReadCharAt Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />