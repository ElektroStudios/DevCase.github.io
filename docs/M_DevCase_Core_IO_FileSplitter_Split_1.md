# FileSplitter.Split Method (Int64, String, String, Boolean, Boolean)
 

Splits a file into chunks of the specified filesize.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Split(
	long chunkSize,
	string chunkName = "",
	string chunkExt = "",
	bool overwrite = false,
	bool deleteAfterSplit = false
)
```

**VB**<br />
``` VB
Public Overridable Sub Split ( 
	chunkSize As Long,
	Optional chunkName As String = "",
	Optional chunkExt As String = "",
	Optional overwrite As Boolean = false,
	Optional deleteAfterSplit As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSplitter
Dim chunkSize As Long
Dim chunkName As String
Dim chunkExt As String
Dim overwrite As Boolean
Dim deleteAfterSplit As Boolean

instance.Split(chunkSize, chunkName, chunkExt, 
	overwrite, deleteAfterSplit)
```

**C++**<br />
``` C++
public:
virtual void Split(
	long long chunkSize, 
	String^ chunkName = L"", 
	String^ chunkExt = L"", 
	bool overwrite = false, 
	bool deleteAfterSplit = false
)
```

**F#**<br />
``` F#
abstract Split : 
        chunkSize : int64 * 
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
        chunkSize : int64 * 
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
&nbsp;<dl><dt>chunkSize</dt><dd>Type: System.Int64<br />The size per chunk, in bytes.</dd><dt>chunkName (Optional)</dt><dd>Type: System.String<br />The name-format for the generated chunks.</dd><dt>chunkExt (Optional)</dt><dd>Type: System.String<br />The file-extension of the generated chunks.</dd><dt>overwrite (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), any existing file will be overwritten if needed to create a chunk, otherwise, an exception will be thrown.</dd><dt>deleteAfterSplit (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the source file will be deleted after a successful split operation.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>The specified source file doesn't exists.</td></tr><tr><td>IOException</td><td>File already exists.</td></tr><tr><td>OverflowException</td><td>'chunkSize' value should be smaller than the source filesize.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSplitter">FileSplitter Class</a><br /><a href="Overload_DevCase_Core_IO_FileSplitter_Split">Split Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />