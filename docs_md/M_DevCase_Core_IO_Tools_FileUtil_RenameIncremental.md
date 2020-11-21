# FileUtil.RenameIncremental Method 
 

Renames all the files of a directory, by enumerating them.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RenameIncremental(
	string directoryPath,
	int zeroCount = 0
)
```

**VB**<br />
``` VB
Public Shared Sub RenameIncremental ( 
	directoryPath As String,
	Optional zeroCount As Integer = 0
)
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As String
Dim zeroCount As Integer

FileUtil.RenameIncremental(directoryPath, 
	zeroCount)
```

**C++**<br />
``` C++
public:
static void RenameIncremental(
	String^ directoryPath, 
	int zeroCount = 0
)
```

**F#**<br />
``` F#
static member RenameIncremental : 
        directoryPath : string * 
        ?zeroCount : int 
(* Defaults:
        let _zeroCount = defaultArg zeroCount 0
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The directory path.</dd><dt>zeroCount (Optional)</dt><dd>Type: System.Int32<br />The zeros amount to enumerate the files. 

 If the value is `0`, the zeros will fit the best amount.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
RenameIncremental("C:\Directory\", zeroCount:=4)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />