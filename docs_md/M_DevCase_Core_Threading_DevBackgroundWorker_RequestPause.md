# DevBackgroundWorker.RequestPause Method 
 

Asynchronously requests to pause a pending background operation. 

 To pause the background work after requesting a pause, call the <a href="M_DevCase_Core_Threading_DevBackgroundWorker_Pause">Pause()</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void RequestPause()
```

**VB**<br />
``` VB
Public Overridable Sub RequestPause
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevBackgroundWorker

instance.RequestPause()
```

**C++**<br />
``` C++
public:
virtual void RequestPause()
```

**F#**<br />
``` F#
abstract RequestPause : unit -> unit 
override RequestPause : unit -> unit 
```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td>In order to request a pause of the BackgroundWorker, the background operation must be running.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker Class</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />