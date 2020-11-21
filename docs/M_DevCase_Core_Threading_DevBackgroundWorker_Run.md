# DevBackgroundWorker.Run Method 
 

Starts execution of a background operation. 

 It blocks the caller thread until the background work is done.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Run()
```

**VB**<br />
``` VB
Public Overridable Sub Run
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevBackgroundWorker

instance.Run()
```

**C++**<br />
``` C++
public:
virtual void Run()
```

**F#**<br />
``` F#
abstract Run : unit -> unit 
override Run : unit -> unit 
```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td>In order to run the BackgroundWorker, the background operation must be stopped or completed.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker Class</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />