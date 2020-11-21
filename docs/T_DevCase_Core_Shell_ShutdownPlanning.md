# ShutdownPlanning Enumeration
 

Specifies a shutdown planning.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ShutdownPlanning
```

**VB**<br />
``` VB
Public Enumeration ShutdownPlanning
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShutdownPlanning
```

**C++**<br />
``` C++
public enum class ShutdownPlanning
```

**F#**<br />
``` F#
type ShutdownPlanning
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownPlanning.Unplanned">**Unplanned**</td><td>0</td><td>The shutdown was unplanned.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownPlanning.UserDefined">**UserDefined**</td><td>1073741824</td><td>The reason code is defined by the user. 

 If this flag is not present, the reason code is defined by the system.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownPlanning.Planned">**Planned**</td><td>2147483648</td><td>The shutdown was planned. 

 If this flag is not present, the shutdown was unplanned. 

 The system generates a System State Data (SSD) file. This file contains system state information such as the processes, threads, memory usage, and configuration.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />