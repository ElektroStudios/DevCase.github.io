# PreventShutdownContext Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Shell_PreventShutdownContext">PreventShutdownContext</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PreventShutdownContext(
	string reason,
	bool throwOnError = true
)
```

**VB**<br />
``` VB
Public Sub New ( 
	reason As String,
	Optional throwOnError As Boolean = true
)
```

**VB Usage**<br />
``` VB Usage
Dim reason As String
Dim throwOnError As Boolean

Dim instance As New PreventShutdownContext(reason, 
	throwOnError)
```

**C++**<br />
``` C++
public:
PreventShutdownContext(
	String^ reason, 
	bool throwOnError = true
)
```

**F#**<br />
``` F#
new : 
        reason : string * 
        ?throwOnError : bool 
(* Defaults:
        let _throwOnError = defaultArg throwOnError true
*)
-> PreventShutdownContext
```


#### Parameters
&nbsp;<dl><dt>reason</dt><dd>Type: System.String<br />The reason for which the current application must prevent system shutdown. 

 Because users are typically in a hurry when shutting down the system, they may spend only a few seconds looking at the shutdown reasons that are displayed by the system. Therefore, it is important that your reason strings are short and clear.</dd><dt>throwOnError (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), an exception will be thrown if the application does not meet the requirements to prevent a system shutdown. 

 Default value is `true` (`True` in Visual Basic).</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td>Applications without a user interface can't prevent a system shutdown.</td></tr><tr><td>InvalidOperationException</td><td>The main window of the current application is not yet created or is not visible.</td></tr><tr><td>InvalidOperationException</td><td>Only the thread that created the main window of the current application can call this to prevent a system shutdown.</td></tr><tr><td>SecurityException</td><td>The user does not have the permissions required to create or modify 'AutoEndTasks' registry value. Therefore, the application can't prevent a system shutdown.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_PreventShutdownContext">PreventShutdownContext Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />