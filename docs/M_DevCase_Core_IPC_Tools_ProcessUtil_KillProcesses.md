# ProcessUtil.KillProcesses Method 
 

Kills all the ocurrence found of running processes with the specified name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool KillProcesses(
	string processName,
	bool killChildProcesses = false,
	bool throwOnProcessNotFound = false
)
```

**VB**<br />
``` VB
Public Shared Function KillProcesses ( 
	processName As String,
	Optional killChildProcesses As Boolean = false,
	Optional throwOnProcessNotFound As Boolean = false
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim processName As String
Dim killChildProcesses As Boolean
Dim throwOnProcessNotFound As Boolean
Dim returnValue As Boolean

returnValue = ProcessUtil.KillProcesses(processName, 
	killChildProcesses, throwOnProcessNotFound)
```

**C++**<br />
``` C++
public:
static bool KillProcesses(
	String^ processName, 
	bool killChildProcesses = false, 
	bool throwOnProcessNotFound = false
)
```

**F#**<br />
``` F#
static member KillProcesses : 
        processName : string * 
        ?killChildProcesses : bool * 
        ?throwOnProcessNotFound : bool 
(* Defaults:
        let _killChildProcesses = defaultArg killChildProcesses false
        let _throwOnProcessNotFound = defaultArg throwOnProcessNotFound false
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>processName</dt><dd>Type: System.String<br />The process name.</dd><dt>killChildProcesses (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), also kills any child process of the found processes.</dd><dt>throwOnProcessNotFound (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), throws an ArgumentException exception if any process was found with the specified name.</dd></dl>

#### Return Value
Type: Boolean<br />if successful `true` (`True` in Visual Basic); `false` (`False` in Visual Basic) if the at least one of the found process does not have a main window, or if *throwOnProcessNotFound* is `false` (`False` in Visual Basic) and any process was found with the specified name.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Any process found with the specified name.;processName</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />