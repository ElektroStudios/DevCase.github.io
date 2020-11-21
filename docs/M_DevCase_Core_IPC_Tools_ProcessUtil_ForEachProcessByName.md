# ProcessUtil.ForEachProcessByName Method 
 

Performs an action on all the Process objects found of running processes with the specified name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ForEachProcessByName(
	string processName,
	Action<Process> predicate,
	bool throwOnProcessNotFound = false
)
```

**VB**<br />
``` VB
Public Shared Sub ForEachProcessByName ( 
	processName As String,
	predicate As Action(Of Process),
	Optional throwOnProcessNotFound As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim processName As String
Dim predicate As Action(Of Process)
Dim throwOnProcessNotFound As BooleanProcessUtil.ForEachProcessByName(processName, 
	predicate, throwOnProcessNotFound)
```

**C++**<br />
``` C++
public:
static void ForEachProcessByName(
	String^ processName, 
	Action<Process^>^ predicate, 
	bool throwOnProcessNotFound = false
)
```

**F#**<br />
``` F#
static member ForEachProcessByName : 
        processName : string * 
        predicate : Action<Process> * 
        ?throwOnProcessNotFound : bool 
(* Defaults:
        let _throwOnProcessNotFound = defaultArg throwOnProcessNotFound false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>processName</dt><dd>Type: System.String<br />The process name.</dd><dt>predicate</dt><dd>Type: System.Action(Process)<br />A transform function to apply to each process found.</dd><dt>throwOnProcessNotFound (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), throws an ArgumentException exception if any process was found with the specified name.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>No processes found with the specified name.;processName</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
ForEachProcessByName("notepad.exe", Sub(p As Process) p.PriorityClass = ProcessPriorityClass.Normal, throwOnProcessNotFound:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />