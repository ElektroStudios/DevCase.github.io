# ProcessUtil.CloseProcesses Method 
 

Closes all the ocurrences found of running processes with the specified name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool CloseProcesses(
	string processName,
	bool throwOnProcessNotFound = false
)
```

**VB**<br />
``` VB
Public Shared Function CloseProcesses ( 
	processName As String,
	Optional throwOnProcessNotFound As Boolean = false
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim processName As String
Dim throwOnProcessNotFound As Boolean
Dim returnValue As Boolean

returnValue = ProcessUtil.CloseProcesses(processName, 
	throwOnProcessNotFound)
```

**C++**<br />
``` C++
public:
static bool CloseProcesses(
	String^ processName, 
	bool throwOnProcessNotFound = false
)
```

**F#**<br />
``` F#
static member CloseProcesses : 
        processName : string * 
        ?throwOnProcessNotFound : bool 
(* Defaults:
        let _throwOnProcessNotFound = defaultArg throwOnProcessNotFound false
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>processName</dt><dd>Type: System.String<br />The process name.</dd><dt>throwOnProcessNotFound (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), throws an ArgumentException exception if any process was found with the specified name.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the close message was successfully sent for all the process ocurrences; `false` (`False` in Visual Basic) if the at least one of the found process does not have a main window, or if the main window is disabled (for example if a modal dialog is being shown), or if *throwOnProcessNotFound* is `false` (`False` in Visual Basic) and any process was found with the specified name.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Any process found with the specified name.;processName</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />