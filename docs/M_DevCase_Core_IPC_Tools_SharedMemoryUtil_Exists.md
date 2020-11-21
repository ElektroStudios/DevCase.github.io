# SharedMemoryUtil.Exists Method 
 

Determine whether a MemoryMappedFile with the specified name is already created.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Exists(
	string name
)
```

**VB**<br />
``` VB
Public Shared Function Exists ( 
	name As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim returnValue As Boolean

returnValue = SharedMemoryUtil.Exists(name)
```

**C++**<br />
``` C++
public:
static bool Exists(
	String^ name
)
```

**F#**<br />
``` F#
static member Exists : 
        name : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name o the MemoryMappedFile segment.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if a MemoryMappedFile with the specified name is already created; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Using mmf As MemoryMappedFile = SharedMemoryUtil.Create("My MemoryMappedFile Name", capacity:=4096)

    Dim exists As Boolean = SharedMemoryUtil.Exists("My MemoryMappedFile Name")
    MessageBox.Show(exists)

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_SharedMemoryUtil">SharedMemoryUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />