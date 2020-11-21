# MutexScope Enumeration
 

Specifies the visibility scope for a Mutex object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MutexScope
```

**VB**<br />
``` VB
Public Enumeration MutexScope
```

**VB Usage**<br />
``` VB Usage
Dim instance As MutexScope
```

**C++**<br />
``` C++
public enum class MutexScope
```

**F#**<br />
``` F#
type MutexScope
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Application.MutexScope.Global">**Global**</td><td>0</td><td>The mutex is visible in all terminal server sessions.</td></tr><tr><td /><td target="F:DevCase.Core.Application.MutexScope.Local">**Local**</td><td>1</td><td>The mutex is visible only in the terminal server session where it was created.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/system.threading.mutex%28v=vs.110%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/system.threading.mutex%28v=vs.110%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />