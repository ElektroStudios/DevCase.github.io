# PowerUtil.LogOff Method 
 

Shuts down all processes running in the logon session and then logs off the interactive user.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool LogOff(
	LogOffMode mode = LogOffMode.ForceIfHung,
	ShutdownReason reason = ShutdownReason.Other,
	bool ignoreErrors = true
)
```

**VB**<br />
``` VB
Public Shared Function LogOff ( 
	Optional mode As LogOffMode = LogOffMode.ForceIfHung,
	Optional reason As ShutdownReason = ShutdownReason.Other,
	Optional ignoreErrors As Boolean = true
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim mode As LogOffMode
Dim reason As ShutdownReason
Dim ignoreErrors As Boolean
Dim returnValue As Boolean

returnValue = PowerUtil.LogOff(mode, reason, 
	ignoreErrors)
```

**C++**<br />
``` C++
public:
static bool LogOff(
	LogOffMode mode = LogOffMode::ForceIfHung, 
	ShutdownReason reason = ShutdownReason::Other, 
	bool ignoreErrors = true
)
```

**F#**<br />
``` F#
static member LogOff : 
        ?mode : LogOffMode * 
        ?reason : ShutdownReason * 
        ?ignoreErrors : bool 
(* Defaults:
        let _mode = defaultArg mode LogOffMode.ForceIfHung
        let _reason = defaultArg reason ShutdownReason.Other
        let _ignoreErrors = defaultArg ignoreErrors true
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>mode (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_LogOffMode">DevCase.Core.Shell.LogOffMode</a><br />Indicates whether to force the logoff.</dd><dt>reason (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_ShutdownReason">DevCase.Core.Shell.ShutdownReason</a><br />The reason for initiating the shutdown.</dd><dt>ignoreErrors (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), a Win32Exception exception will be thrown if error found.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 The function executes asynchronously so a `true` (`True` in Visual Basic) return value indicates that the shutdown has been initiated. 

 It does not indicate whether the shutdown will succeed. It is possible that the system, the user, or another application will abort the shutdown. 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />