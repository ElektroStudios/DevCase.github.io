# DevBackgroundWorkerState Enumeration
 

Specifies the state of a <a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum DevBackgroundWorkerState
```

**VB**<br />
``` VB
Public Enumeration DevBackgroundWorkerState
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevBackgroundWorkerState
```

**C++**<br />
``` C++
public enum class DevBackgroundWorkerState
```

**F#**<br />
``` F#
type DevBackgroundWorkerState
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Threading.DevBackgroundWorkerState.Stopped">**Stopped**</td><td>0</td><td>The <a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker</a> is stopped.</td></tr><tr><td /><td target="F:DevCase.Core.Threading.DevBackgroundWorkerState.Running">**Running**</td><td>1</td><td>The <a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker</a> is running.</td></tr><tr><td /><td target="F:DevCase.Core.Threading.DevBackgroundWorkerState.Paused">**Paused**</td><td>2</td><td>The <a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker</a> is paused.</td></tr><tr><td /><td target="F:DevCase.Core.Threading.DevBackgroundWorkerState.CancellationPending">**CancellationPending**</td><td>3</td><td>The <a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker</a> is pending on a cancellation.</td></tr><tr><td /><td target="F:DevCase.Core.Threading.DevBackgroundWorkerState.Completed">**Completed**</td><td>4</td><td>The <a href="T_DevCase_Core_Threading_DevBackgroundWorker">DevBackgroundWorker</a> is completed (stopped).</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />