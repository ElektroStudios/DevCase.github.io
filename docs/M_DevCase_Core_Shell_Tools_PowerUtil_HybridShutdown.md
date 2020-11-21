# PowerUtil.HybridShutdown Method 
 

Shutdowns the specified computer and prepares the system for a faster startup. 

 Use this function only for Windows 8/8.1

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool HybridShutdown(
	string computer = "",
	int timeout = 0,
	string message = "",
	ShutdownMode mode = ShutdownMode.Wait,
	ShutdownReason reason = ShutdownReason.Other,
	ShutdownPlanning planning = ShutdownPlanning.Unplanned,
	bool ignoreErrors = true
)
```

**VB**<br />
``` VB
Public Shared Function HybridShutdown ( 
	Optional computer As String = "",
	Optional timeout As Integer = 0,
	Optional message As String = "",
	Optional mode As ShutdownMode = ShutdownMode.Wait,
	Optional reason As ShutdownReason = ShutdownReason.Other,
	Optional planning As ShutdownPlanning = ShutdownPlanning.Unplanned,
	Optional ignoreErrors As Boolean = true
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim computer As String
Dim timeout As Integer
Dim message As String
Dim mode As ShutdownMode
Dim reason As ShutdownReason
Dim planning As ShutdownPlanning
Dim ignoreErrors As Boolean
Dim returnValue As Boolean

returnValue = PowerUtil.HybridShutdown(computer, 
	timeout, message, mode, reason, planning, 
	ignoreErrors)
```

**C++**<br />
``` C++
public:
static bool HybridShutdown(
	String^ computer = L"", 
	int timeout = 0, 
	String^ message = L"", 
	ShutdownMode mode = ShutdownMode::Wait, 
	ShutdownReason reason = ShutdownReason::Other, 
	ShutdownPlanning planning = ShutdownPlanning::Unplanned, 
	bool ignoreErrors = true
)
```

**F#**<br />
``` F#
static member HybridShutdown : 
        ?computer : string * 
        ?timeout : int * 
        ?message : string * 
        ?mode : ShutdownMode * 
        ?reason : ShutdownReason * 
        ?planning : ShutdownPlanning * 
        ?ignoreErrors : bool 
(* Defaults:
        let _computer = defaultArg computer ""
        let _timeout = defaultArg timeout 0
        let _message = defaultArg message ""
        let _mode = defaultArg mode ShutdownMode.Wait
        let _reason = defaultArg reason ShutdownReason.Other
        let _planning = defaultArg planning ShutdownPlanning.Unplanned
        let _ignoreErrors = defaultArg ignoreErrors true
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>computer (Optional)</dt><dd>Type: System.String<br />The name of the computer to be shut down. 

 If the value of this parameter is an empty string, the local computer is shut down. 

 This parameter can be an addres, for example: `127.0.0.1`</dd><dt>timeout (Optional)</dt><dd>Type: System.Int32<br />The number of seconds to wait before shutting down the computer. 

 If the value of this parameter is zero, the computer is shut down immediately. 

 This value is limited to <a href="F_DevCase_Core_Shell_Tools_PowerUtil_MaxShutdownTimeout">MaxShutdownTimeout</a>.</dd><dt>message (Optional)</dt><dd>Type: System.String<br />The message to be displayed in the interactive shutdown dialog box.</dd><dt>mode (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_ShutdownMode">DevCase.Core.Shell.ShutdownMode</a><br />Indicates whether to force the shutdown.</dd><dt>reason (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_ShutdownReason">DevCase.Core.Shell.ShutdownReason</a><br />The reason for initiating the shutdown. By default, it is also an 'unplanned' shutdown. 

 If this parameter is zero, the default is an undefined shutdown that is logged as "No title for this reason could be found".</dd><dt>planning (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_ShutdownPlanning">DevCase.Core.Shell.ShutdownPlanning</a><br />Indicates whether it's a planned or unplanned shutdoen operation.</dd><dt>ignoreErrors (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), a Win32Exception exception will be thrown if error found.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the hydrid shutdown operation is initiated correctlly, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Timeout should be zero or greater than zero.;timeout</td></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />