# FileSplitter.Split Method (Int32, String, String, Boolean, Boolean)
 

Splits a file into the specified amount of chunks.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Split(
	int chunkCount,
	string chunkName = "",
	string chunkExt = "",
	bool overwrite = false,
	bool deleteAfterSplit = false
)
```

**VB**<br />
``` VB
Public Overridable Sub Split ( 
	chunkCount As Integer,
	Optional chunkName As String = "",
	Optional chunkExt As String = "",
	Optional overwrite As Boolean = false,
	Optional deleteAfterSplit As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSplitter
Dim chunkCount As Integer
Dim chunkName As String
Dim chunkExt As String
Dim overwrite As Boolean
Dim deleteAfterSplit As Boolean

instance.Split(chunkCount, chunkName, 
	chunkExt, overwrite, deleteAfterSplit)
```

**C++**<br />
``` C++
public:
virtual void Split(
	int chunkCount, 
	String^ chunkName = L"", 
	String^ chunkExt = L"", 
	bool overwrite = false, 
	bool deleteAfterSplit = false
)
```

**F#**<br />
``` F#
abstract Split : 
        chunkCount : int * 
        ?chunkName : string * 
        ?chunkExt : string * 
        ?overwrite : bool * 
        ?deleteAfterSplit : bool 
(* Defaults:
        let _chunkName = defaultArg chunkName ""
        let _chunkExt = defaultArg chunkExt ""
        let _overwrite = defaultArg overwrite false
        let _deleteAfterSplit = defaultArg deleteAfterSplit false
*)
-> unit 
override Split : 
        chunkCount : int * 
        ?chunkName : string * 
        ?chunkExt : string * 
        ?overwrite : bool * 
        ?deleteAfterSplit : bool 
(* Defaults:
        let _chunkName = defaultArg chunkName ""
        let _chunkExt = defaultArg chunkExt ""
        let _overwrite = defaultArg overwrite false
        let _deleteAfterSplit = defaultArg deleteAfterSplit false
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>chunkCount</dt><dd>Type: System.Int32<br />The amount of chunks to generate.</dd><dt>chunkName (Optional)</dt><dd>Type: System.String<br />The name-format for the generated chunks.</dd><dt>chunkExt (Optional)</dt><dd>Type: System.String<br />The file-extension of the generated chunks.</dd><dt>overwrite (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), any existing file will be overwritten if needed to create a chunk, otherwise, an exception will be thrown.</dd><dt>deleteAfterSplit (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the source file will be deleted after a successful split operation.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSplitter">FileSplitter Class</a><br /><a href="Overload_DevCase_Core_IO_FileSplitter_Split">Split Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />