# PowerUtil.Restart Method 
 

Restarts the specified computer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Restart(
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
Public Shared Function Restart ( 
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

returnValue = PowerUtil.Restart(computer, 
	timeout, message, mode, reason, planning, 
	ignoreErrors)
```

**C++**<br />
``` C++
public:
static bool Restart(
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
static member Restart : 
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
&nbsp;<dl><dt>computer (Optional)</dt><dd>Type: System.String<br />The name of the computer to restart. 

 If the value of this parameter is an empty string, the local computer is shut down. 

 This parameter can be an addres, for example: `127.0.0.1`</dd><dt>timeout (Optional)</dt><dd>Type: System.Int32<br />The number of seconds to wait before restarting the computer. 

 If the value of this parameter is zero, the computer is restarted immediately. 

 This value is limited to <a href="F_DevCase_Core_Shell_Tools_PowerUtil_MaxShutdownTimeout">MaxShutdownTimeout</a>.</dd><dt>message (Optional)</dt><dd>Type: System.String<br />The message to be displayed in the interactive restart dialog box.</dd><dt>mode (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_ShutdownMode">DevCase.Core.Shell.ShutdownMode</a><br />Indicates whether to force the restart.</dd><dt>reason (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_ShutdownReason">DevCase.Core.Shell.ShutdownReason</a><br />The reason for initiating the restart. By default, it is also an 'unplanned' restart. 

 If this parameter is zero, the default is an undefined restart that is logged as "No title for this reason could be found".</dd><dt>planning (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_ShutdownPlanning">DevCase.Core.Shell.ShutdownPlanning</a><br />Indicates whether it's a planned or unplanned restart operation.</dd><dt>ignoreErrors (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), a Win32Exception exception will be thrown if error found.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the restart operation is initiated correctlly, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Timeout should be zero or greater than zero.;timeout</td></tr><tr><td>Win32Exception</td><td /></tr></table>

## Examples
This is a code example that tries to restart the operating system, then abort the restart operation. 
**VB**<br />
``` VB
' Restart the current computer in 60 seconds and wait for applications to close.
' Specify that the restart operation is planned because a consecuence of an installation.
Dim success As Boolean =
    PowerUtil.Restart(Nothing, 60, "System is gonna be restarted quickly, go save all your data now...!",
                      ShutdownMode.Wait,
                      ShutdownReason.MajorOperatingSystem Or
                      ShutdownReason.MinorInstallation,
                      ShutdownPlanning.Planned)

Console.WriteLine(String.Format("Restart operation initiated successfully?: {0}", CStr(success)))

' Abort the current operation.
If success Then
    Dim isAborted As Boolean = Abort(computer:=Nothing, ignoreErrors:=False)
    Console.WriteLine(String.Format("Restart operation aborted   successfully?: {0}", CStr(isAborted)))
Else
    Console.WriteLine("There is any restart operation to abort.")
End If

If MessageBox.Show("Want to proceed inmediately with a shutdown that cannot be aborted ?", "",
                   MessageBoxButtons.YesNo, MessageBoxIcon.Warning, MessageBoxDefaultButton.Button2) = Windows.Forms.DialogResult.Yes Then

    ' Shutdown the current computer instantlly and force applications to close.
    ' ( When timeout is '0' the operation can't be aborted )
    PowerUtil.Shutdown(Nothing, 0, Nothing, ShutdownMode.ForceSelf)

    ' LogOffs the current user.
    PowerUtil.LogOff(LogOffMode.Wait)

End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />