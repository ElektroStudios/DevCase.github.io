# ChangeDisplaySettingsFlags Enumeration
 

Flags combination for `flags` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeDisplaySettingsEx">ChangeDisplaySettingsEx(String, DevMode, IntPtr, ChangeDisplaySettingsFlags, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ChangeDisplaySettingsFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ChangeDisplaySettingsFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ChangeDisplaySettingsFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ChangeDisplaySettingsFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ChangeDisplaySettingsFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.None">**None**</td><td>0</td><td>The graphics mode for the current screen will be changed dynamically.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.UpdateRegistry">**UpdateRegistry**</td><td>1</td><td>The graphics mode for the current screen will be changed dynamically and the graphics mode will be updated in the registry. 

 The mode information is stored in the USER profile.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.Test">**Test**</td><td>2</td><td>The system tests if the requested graphics mode could be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.Fullscreen">**Fullscreen**</td><td>4</td><td>The mode is temporary in nature. 

 If you change to and from another desktop, this mode will not be reset.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.Global">**Global**</td><td>8</td><td>The settings will be saved in the global settings area so that they will affect all users on the machine. 

 Otherwise, only the settings for the user are modified. 

 This flag is only valid when specified with the UpdateRegistry flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.SetPrimary">**SetPrimary**</td><td>16</td><td>This device will become the primary device.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.VideoParameters">**VideoParameters**</td><td>32</td><td>When set, the `lParam` parameter is a pointer to a `VIDEOPARAMETERS` structure.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.EnableUnsafeModes">**EnableUnsafeModes**</td><td>256</td><td>Enables settings changes to unsafe graphics modes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.DisableUnsafeModes">**DisableUnsafeModes**</td><td>512</td><td>Disables settings changes to unsafe graphics modes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.Reset">**Reset**</td><td>1073741824</td><td>The settings should be changed, even if the requested settings are the same as the current settings.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.ResetEx">**ResetEx**</td><td>536870912</td><td>Not documented.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags.NoReset">**NoReset**</td><td>268435456</td><td>The settings will be saved in the registry, but will not take effect. 

 This flag is only valid when specified with the UpdateRegistry flag.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183413%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183413%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />