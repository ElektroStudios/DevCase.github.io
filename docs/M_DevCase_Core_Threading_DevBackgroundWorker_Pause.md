# DevBackgroundWorker.Pause Method 
 

Pause a pending background operation. 

 It blocks the caller thread until the background work is resumed. To resume the background work, call the <a href="M_DevCase_Core_Threading_DevBackgroundWorker_Resume">Resume()</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Pause()
```

**VB**<br />
``` VB
Public Overridable Sub Pause
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevBackgroundWorker

instance.Pause()
```

**C++**<br />
``` C++
public:
virtual void Pause()
```

**F#**<br />
``` F#
abstract Pause : unit -> unit 
override Pause : unit -> unit 
```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td>In order to pause the BackgroundWorker, firstly a pause request should be made.</td></tr><tr><td>InvalidOperationException</td><td>In order to pause the BackgroundWorker, the background operation must be be running.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker Class</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />