# ProcessUtil.IsRunning Method 
 

Determines whether exists at least one running process running with the specified name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsRunning(
	string processName
)
```

**VB**<br />
``` VB
Public Shared Function IsRunning ( 
	processName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim processName As String
Dim returnValue As Boolean

returnValue = ProcessUtil.IsRunning(processName)
```

**C++**<br />
``` C++
public:
static bool IsRunning(
	String^ processName
)
```

**F#**<br />
``` F#
static member IsRunning : 
        processName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>processName</dt><dd>Type: System.String<br />The process name.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if exists, at least, one running process with the specified name. `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />