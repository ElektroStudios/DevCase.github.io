# DevBackgroundWorker.CancelAsync Method 
 

Asynchronously requests cancellation of a pending background operation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void CancelAsync()
```

**VB**<br />
``` VB
Public Overridable Sub CancelAsync
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevBackgroundWorker

instance.CancelAsync()
```

**C++**<br />
``` C++
public:
virtual void CancelAsync()
```

**F#**<br />
``` F#
abstract CancelAsync : unit -> unit 
override CancelAsync : unit -> unit 
```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td>In order to cancel the BackgroundWorker, the background operation must be running or paused.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker Class</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />