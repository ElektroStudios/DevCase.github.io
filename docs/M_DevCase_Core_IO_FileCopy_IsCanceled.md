# FileCopy.IsCanceled Method 
 

Determines whether the specified file-copy task was cancelled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool IsCanceled(
	CancellationTokenSource cancellationTokenSource
)
```

**VB**<br />
``` VB
Public Overridable Function IsCanceled ( 
	cancellationTokenSource As CancellationTokenSource
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileCopy
Dim cancellationTokenSource As CancellationTokenSource
Dim returnValue As Boolean

returnValue = instance.IsCanceled(cancellationTokenSource)
```

**C++**<br />
``` C++
public:
virtual bool IsCanceled(
	CancellationTokenSource^ cancellationTokenSource
)
```

**F#**<br />
``` F#
abstract IsCanceled : 
        cancellationTokenSource : CancellationTokenSource -> bool 
override IsCanceled : 
        cancellationTokenSource : CancellationTokenSource -> bool 
```


#### Parameters
&nbsp;<dl><dt>cancellationTokenSource</dt><dd>Type: System.Threading.CancellationTokenSource<br />A CancellationTokenSource instance associateted to a file-copy task.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified file-copy task was cancelled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileCopy">FileCopy Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />