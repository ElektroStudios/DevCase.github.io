# DisplaySettingsChange Enumeration
 

Specifies a result value of a call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeDisplaySettingsEx">ChangeDisplaySettingsEx(String, DevMode, IntPtr, ChangeDisplaySettingsFlags, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum DisplaySettingsChange
```

**VB**<br />
``` VB
Public Enumeration DisplaySettingsChange
```

**VB Usage**<br />
``` VB Usage
Dim instance As DisplaySettingsChange
```

**C++**<br />
``` C++
public enum class DisplaySettingsChange
```

**F#**<br />
``` F#
type DisplaySettingsChange
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplaySettingsChange.Successful">**Successful**</td><td>0</td><td>The settings change was successful.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplaySettingsChange.Restart">**Restart**</td><td>1</td><td>The computer must be restarted for the graphics mode to work.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplaySettingsChange.Failed">**Failed**</td><td>-1</td><td>The display driver failed the specified graphics mode.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplaySettingsChange.BadMode">**BadMode**</td><td>-2</td><td>The graphics mode is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplaySettingsChange.NotUpdated">**NotUpdated**</td><td>-3</td><td>Unable to write settings to the registry.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplaySettingsChange.BadFlags">**BadFlags**</td><td>-4</td><td>An invalid set of flags was passed in.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplaySettingsChange.BadParam">**BadParam**</td><td>-5</td><td>An invalid parameter was passed in. This can include an invalid flag or combination of flags.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplaySettingsChange.BadDualView">**BadDualView**</td><td>-6</td><td>The settings change was unsuccessful because the system is DualView capable.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />