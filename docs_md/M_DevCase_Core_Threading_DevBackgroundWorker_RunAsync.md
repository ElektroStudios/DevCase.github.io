# DevBackgroundWorker.RunAsync Method 
 

Asynchronously starts execution of a background operation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void RunAsync()
```

**VB**<br />
``` VB
Public Overridable Sub RunAsync
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevBackgroundWorker

instance.RunAsync()
```

**C++**<br />
``` C++
public:
virtual void RunAsync()
```

**F#**<br />
``` F#
abstract RunAsync : unit -> unit 
override RunAsync : unit -> unit 
```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td>In order to run the BackgroundWorker, the background operation must be stopped or completed.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker Class</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />