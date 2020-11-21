# ProcessUtil.ForEachProcessByNameGet(*T*) Method 
 

Performs an action on all the Process objects found of running processes with the specified name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<T> ForEachProcessByNameGet<T>(
	string processName,
	Func<Process, T> predicate,
	bool throwOnProcessNotFound = false
)

```

**VB**<br />
``` VB
Public Shared Function ForEachProcessByNameGet(Of T) ( 
	processName As String,
	predicate As Func(Of Process, T),
	Optional throwOnProcessNotFound As Boolean = false
) As IEnumerable(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim processName As String
Dim predicate As Func(Of Process, T)
Dim throwOnProcessNotFound As Boolean
Dim returnValue As IEnumerable(Of T)

returnValue = ProcessUtil.ForEachProcessByNameGet(processName, 
	predicate, throwOnProcessNotFound)
```

**C++**<br />
``` C++
public:
generic<typename T>
static IEnumerable<T>^ ForEachProcessByNameGet(
	String^ processName, 
	Func<Process^, T>^ predicate, 
	bool throwOnProcessNotFound = false
)
```

**F#**<br />
``` F#
static member ForEachProcessByNameGet : 
        processName : string * 
        predicate : Func<Process, 'T> * 
        ?throwOnProcessNotFound : bool 
(* Defaults:
        let _throwOnProcessNotFound = defaultArg throwOnProcessNotFound false
*)
-> IEnumerable<'T> 

```


#### Parameters
&nbsp;<dl><dt>processName</dt><dd>Type: System.String<br />The process name.</dd><dt>predicate</dt><dd>Type: System.Func(Process, *T*)<br />A transform function to apply to each process found.</dd><dt>throwOnProcessNotFound (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), throws an ArgumentException exception if any process was found with the specified name.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The Type of the value to return.</dd></dl>

#### Return Value
Type: IEnumerable(*T*)<br />If successful, the returning value is an IEnumerable(T); otherwise, a null reference (`Nothing` in Visual Basic) if *throwOnProcessNotFound* is `false` (`False` in Visual Basic) and any process was found with the specified name.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Any process found with the specified name.;processName</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pids As IEnumerable(Of Integer) =
    ForEachProcessByNameGet("notepad.exe", Function(p As Process) p.Id, throwOnProcessNotFound:=True)

MessageBox.Show(String.Join(", ", pids))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />