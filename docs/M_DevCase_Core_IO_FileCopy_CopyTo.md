# FileCopy.CopyTo Method 
 

Asynchronously copies the source file to the specified destination.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual CancellationTokenSource CopyTo(
	string targetFilepath,
	int bufferSize = 1024,
	bool overwrite = false,
	bool deleteFileOnCancel = false,
	Action cancelCallback = null
)
```

**VB**<br />
``` VB
Public Overridable Function CopyTo ( 
	targetFilepath As String,
	Optional bufferSize As Integer = 1024,
	Optional overwrite As Boolean = false,
	Optional deleteFileOnCancel As Boolean = false,
	Optional cancelCallback As Action = Nothing
) As CancellationTokenSource
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileCopy
Dim targetFilepath As String
Dim bufferSize As Integer
Dim overwrite As Boolean
Dim deleteFileOnCancel As Boolean
Dim cancelCallback As Action
Dim returnValue As CancellationTokenSource

returnValue = instance.CopyTo(targetFilepath, 
	bufferSize, overwrite, deleteFileOnCancel, 
	cancelCallback)
```

**C++**<br />
``` C++
public:
virtual CancellationTokenSource^ CopyTo(
	String^ targetFilepath, 
	int bufferSize = 1024, 
	bool overwrite = false, 
	bool deleteFileOnCancel = false, 
	Action^ cancelCallback = nullptr
)
```

**F#**<br />
``` F#
abstract CopyTo : 
        targetFilepath : string * 
        ?bufferSize : int * 
        ?overwrite : bool * 
        ?deleteFileOnCancel : bool * 
        ?cancelCallback : Action 
(* Defaults:
        let _bufferSize = defaultArg bufferSize 1024
        let _overwrite = defaultArg overwrite false
        let _deleteFileOnCancel = defaultArg deleteFileOnCancel false
        let _cancelCallback = defaultArg cancelCallback null
*)
-> CancellationTokenSource 
override CopyTo : 
        targetFilepath : string * 
        ?bufferSize : int * 
        ?overwrite : bool * 
        ?deleteFileOnCancel : bool * 
        ?cancelCallback : Action 
(* Defaults:
        let _bufferSize = defaultArg bufferSize 1024
        let _overwrite = defaultArg overwrite false
        let _deleteFileOnCancel = defaultArg deleteFileOnCancel false
        let _cancelCallback = defaultArg cancelCallback null
*)
-> CancellationTokenSource 
```


#### Parameters
&nbsp;<dl><dt>targetFilepath</dt><dd>Type: System.String<br />The target filepath.</dd><dt>bufferSize (Optional)</dt><dd>Type: System.Int32<br />The size, in bytes, of the internal FileStream buffer that is used to copy.</dd><dt>overwrite (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), overwrites any existing file, otherwise, a IOException exception is thrown.</dd><dt>deleteFileOnCancel (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), deletes the target file if the copy operation was cancelled</dd><dt>cancelCallback (Optional)</dt><dd>Type: System.Action<br />A encapsulated method that is called if the copy operation is cancelled.</dd></dl>

#### Return Value
Type: CancellationTokenSource<br />A CancellationTokenSource instance to cancel the file-copy task at any moment. 

 This value can be pass to the <a href="M_DevCase_Core_IO_FileCopy_CancelCopy">CancelCopy(CancellationTokenSource)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File not found.;targetFilepath</td></tr><tr><td>IOException</td><td>Target file already exists.</td></tr><tr><td>ArgumentException</td><td>Positive value is required.;bufferSize</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileCopy">FileCopy Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />