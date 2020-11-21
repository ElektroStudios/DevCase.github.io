# InitiateShutdownFlags Enumeration
 

Flags for `dwShutdownFlags` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InitiateShutdown">InitiateShutdown(String, String, Int32, UInt32, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum InitiateShutdownFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration InitiateShutdownFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As InitiateShutdownFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class InitiateShutdownFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type InitiateShutdownFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.GraceOverride">**GraceOverride**</td><td>32</td><td>Overrides the grace period so that the computer is shut down immediately.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.InstallUpdates">**InstallUpdates**</td><td>64</td><td>The computer installs any updates before starting the shutdown.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.Shutdown">**Shutdown**</td><td>16</td><td>The computer is shut down but is not powered down or restarted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.HybridShutdown">**HybridShutdown**</td><td>512</td><td>( Beginning with Windows 8 ) 

 Prepares the system for a faster startup by combining the HybridShutdown flag with the Shutdown flag. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InitiateShutdown">InitiateShutdown(String, String, Int32, UInt32, UInt32)</a> always initiate a full system shutdown if the HybridShutdown flag is not set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.PowerOff">**PowerOff**</td><td>8</td><td>The computer is shut down and powered down.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.Restart">**Restart**</td><td>4</td><td>The computer is shut down and restarted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.RestartApps">**RestartApps**</td><td>128</td><td>The system is restarted using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ExitWindowsEx">ExitWindowsEx(ExitwindowsExFlags, ShutdownReason)</a> function with the RestartApps flag. 

 This restarts any applications that have been registered for restart using the `RegisterApplicationRestart` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.Wait">**Wait**</td><td>0</td><td>Don't force the system to close the applications. 

 This is the default parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.ForceOthers">**ForceOthers**</td><td>1</td><td>All sessions are forcefully logged off. 

 If this flag is not set and users other than the current user are logged on to the computer specified by the `lpMachineName` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.InitiateShutdownFlags.ForceSelf">**ForceSelf**</td><td>2</td><td>Specifies that the originating session is logged off forcefully. 

 If this flag is not set, the originating session is shut down interactively, so a shutdown is not guaranteed even if the function returns successfully.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa376872%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa376872%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />