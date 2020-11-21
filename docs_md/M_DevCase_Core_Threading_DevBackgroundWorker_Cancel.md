# DevBackgroundWorker.Cancel Method 
 

Requests cancellation of a pending background operation. 

 It blocks the caller thread until the remaining background work is canceled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Cancel()
```

**VB**<br />
``` VB
Public Overridable Sub Cancel
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevBackgroundWorker

instance.Cancel()
```

**C++**<br />
``` C++
public:
virtual void Cancel()
```

**F#**<br />
``` F#
abstract Cancel : unit -> unit 
override Cancel : unit -> unit 
```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td>In order to cancel the BackgroundWorker, the background operation must be running or paused.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker Class</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />