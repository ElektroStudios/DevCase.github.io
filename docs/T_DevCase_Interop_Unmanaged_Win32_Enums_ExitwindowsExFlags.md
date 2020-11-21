# ExitwindowsExFlags Enumeration
 

Flags for `uFlags` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ExitWindowsEx">ExitWindowsEx(ExitwindowsExFlags, ShutdownReason)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ExitwindowsExFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ExitwindowsExFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ExitwindowsExFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ExitwindowsExFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ExitwindowsExFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExitwindowsExFlags.LogOff">**LogOff**</td><td>0</td><td>Shuts down all processes running in the logon session of the current process. Then it logs the user off. 

 This flag can be used only by processes running in an interactive user's logon session.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExitwindowsExFlags.ShutDown">**ShutDown**</td><td>1</td><td>Shuts down the system to a point at which it is safe to turn off the power. 

 All file buffers have been flushed to disk, and all running processes have stopped. The calling process must have the `SE_SHUTDOWN_NAME` privilege. 

 Specifying this flag will not turn off the power even if the system supports the power-off feature, You must use PowerOff to do this.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExitwindowsExFlags.HybridShutdown">**HybridShutdown**</td><td>4194304</td><td>( Beginning with Windows 8 ) 

 You can prepare the system for a faster startup by combining the HybridShutdown flag with the ShutDown flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExitwindowsExFlags.Reboot">**Reboot**</td><td>2</td><td>Shuts down the system and then restarts the system. 

 The calling process must have the `SE_SHUTDOWN_NAME` privilege</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExitwindowsExFlags.PowerOff">**PowerOff**</td><td>8</td><td>Shuts down the system and turns off the power. 

 The system must support the power-off feature. 

 The calling process must have the `SE_SHUTDOWN_NAME` privilege.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExitwindowsExFlags.RestartApps">**RestartApps**</td><td>64</td><td>Shuts down the system and then restarts it, as well as any applications that have been registered for restart using the `RegisterApplicationRestart` function. 

 These application receive the `WM_QUERYENDSESSION` message with lParam set to the `ENDSESSION_CLOSEAPP` value. 

 For more information, see Guidelines for Applications: <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa373651%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa373651%28v=vs.85%29.aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExitwindowsExFlags.Force">**Force**</td><td>4</td><td>This flag has no effect if terminal services is enabled. 

 Otherwise, the system does not send the `WM_QUERYENDSESSION` message. 

 This can cause applications to lose data. Therefore, you should only use this flag in an emergency.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExitwindowsExFlags.ForceIfHung">**ForceIfHung**</td><td>16</td><td>Forces processes to terminate if they do not respond to the `WM_QUERYENDSESSION` or `WM_ENDSESSION` message within the timeout interval.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa376868%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa376868%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />