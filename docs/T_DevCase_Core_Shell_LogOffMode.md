# LogOffMode Enumeration
 

Specifies the mode to logoff an user session.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum LogOffMode
```

**VB**<br />
``` VB
Public Enumeration LogOffMode
```

**VB Usage**<br />
``` VB Usage
Dim instance As LogOffMode
```

**C++**<br />
``` C++
public enum class LogOffMode
```

**F#**<br />
``` F#
type LogOffMode
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Shell.LogOffMode.Wait">**Wait**</td><td>0</td><td>Don't force the system to close the applications.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.LogOffMode.Force">**Force**</td><td>4</td><td>This flag has no effect if terminal services is enabled. Otherwise, the system does not send the `WM_QUERYENDSESSION` message. 

 This can cause applications to lose data. Therefore, you should only use this flag in an emergency.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.LogOffMode.ForceIfHung">**ForceIfHung**</td><td>16</td><td>Forces processes to terminate if they do not respond to the `WM_QUERYENDSESSION` or `WM_ENDSESSION` message within the timeout interval.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />