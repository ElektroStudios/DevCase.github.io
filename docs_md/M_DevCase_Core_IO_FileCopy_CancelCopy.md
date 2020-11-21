# FileCopy.CancelCopy Method 
 

Cancels a file-copy operation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void CancelCopy(
	CancellationTokenSource cancellationTokenSource
)
```

**VB**<br />
``` VB
Public Overridable Sub CancelCopy ( 
	cancellationTokenSource As CancellationTokenSource
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileCopy
Dim cancellationTokenSource As CancellationTokenSource

instance.CancelCopy(cancellationTokenSource)
```

**C++**<br />
``` C++
public:
virtual void CancelCopy(
	CancellationTokenSource^ cancellationTokenSource
)
```

**F#**<br />
``` F#
abstract CancelCopy : 
        cancellationTokenSource : CancellationTokenSource -> unit 
override CancelCopy : 
        cancellationTokenSource : CancellationTokenSource -> unit 
```


#### Parameters
&nbsp;<dl><dt>cancellationTokenSource</dt><dd>Type: System.Threading.CancellationTokenSource<br />A CancellationTokenSource instance associateted to a file-copy task.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>OperationCanceledException</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileCopy">FileCopy Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />