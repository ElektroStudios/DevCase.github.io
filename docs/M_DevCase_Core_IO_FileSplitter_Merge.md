# FileSplitter.Merge Method 
 

Merges the chunks of a previously splitted file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Merge(
	string targetFile = "",
	bool overwrite = false,
	bool deleteChunksAfterMerged = false
)
```

**VB**<br />
``` VB
Public Overridable Sub Merge ( 
	Optional targetFile As String = "",
	Optional overwrite As Boolean = false,
	Optional deleteChunksAfterMerged As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSplitter
Dim targetFile As String
Dim overwrite As Boolean
Dim deleteChunksAfterMerged As Boolean

instance.Merge(targetFile, overwrite, 
	deleteChunksAfterMerged)
```

**C++**<br />
``` C++
public:
virtual void Merge(
	String^ targetFile = L"", 
	bool overwrite = false, 
	bool deleteChunksAfterMerged = false
)
```

**F#**<br />
``` F#
abstract Merge : 
        ?targetFile : string * 
        ?overwrite : bool * 
        ?deleteChunksAfterMerged : bool 
(* Defaults:
        let _targetFile = defaultArg targetFile ""
        let _overwrite = defaultArg overwrite false
        let _deleteChunksAfterMerged = defaultArg deleteChunksAfterMerged false
*)
-> unit 
override Merge : 
        ?targetFile : string * 
        ?overwrite : bool * 
        ?deleteChunksAfterMerged : bool 
(* Defaults:
        let _targetFile = defaultArg targetFile ""
        let _overwrite = defaultArg overwrite false
        let _deleteChunksAfterMerged = defaultArg deleteChunksAfterMerged false
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>targetFile (Optional)</dt><dd>Type: System.String<br />The target filepath.</dd><dt>overwrite (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), in case that the specified file in *targetFile* exists it will be overwritten, otherwise, an exception will be thrown.</dd><dt>deleteChunksAfterMerged (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the chunks will be deleted after a successful merge operation.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>The specified source chunk file doesn't exists.</td></tr><tr><td>FileNotFoundException</td><td>Only one chunk file found, the last chunk file is missing.</td></tr><tr><td>IOException</td><td>The specified target file already exists.</td></tr><tr><td>OverflowException</td><td>Unexpected chunk filesize-count detected, maybe one of the chunk files is corrupt?.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSplitter">FileSplitter Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />