# PowerUtil.AbortShutdown Method 
 

Aborts a system shutdown operation that has been initiated (unless a LogOff).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AbortShutdown(
	string computer = "",
	bool ignoreErrors = true
)
```

**VB**<br />
``` VB
Public Shared Function AbortShutdown ( 
	Optional computer As String = "",
	Optional ignoreErrors As Boolean = true
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim computer As String
Dim ignoreErrors As Boolean
Dim returnValue As Boolean

returnValue = PowerUtil.AbortShutdown(computer, 
	ignoreErrors)
```

**C++**<br />
``` C++
public:
static bool AbortShutdown(
	String^ computer = L"", 
	bool ignoreErrors = true
)
```

**F#**<br />
``` F#
static member AbortShutdown : 
        ?computer : string * 
        ?ignoreErrors : bool 
(* Defaults:
        let _computer = defaultArg computer ""
        let _ignoreErrors = defaultArg ignoreErrors true
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>computer (Optional)</dt><dd>Type: System.String<br />The network name of the computer where the shutdown is to be stopped. 

 If this parameter is an empty string, the function aborts the shutdown on the local computer.</dd><dt>ignoreErrors (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), a Win32Exception exception will be thrown if error found.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />