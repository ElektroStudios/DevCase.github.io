# ShutdownMode Enumeration
 

Specifies the mode to shutdown/restart the system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ShutdownMode
```

**VB**<br />
``` VB
Public Enumeration ShutdownMode
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShutdownMode
```

**C++**<br />
``` C++
public enum class ShutdownMode
```

**F#**<br />
``` F#
type ShutdownMode
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownMode.Wait">**Wait**</td><td>0</td><td>Don't force the system to close the applications.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownMode.ForceOthers">**ForceOthers**</td><td>1</td><td>All sessions are forcefully logged off.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownMode.ForceSelf">**ForceSelf**</td><td>2</td><td>Specifies that the originating session is logged off forcefully. 

 If this flag is not set, the originating session is shut down interactively, so a shutdown is not guaranteed.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />