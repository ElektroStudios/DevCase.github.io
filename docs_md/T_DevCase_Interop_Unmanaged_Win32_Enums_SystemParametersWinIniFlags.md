# SystemParametersWinIniFlags Enumeration
 

Flags for `fWinIni` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SystemParametersInfo">SystemParametersInfo(SystemParametersActionFlags, Boolean, Boolean, SystemParametersWinIniFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SystemParametersWinIniFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SystemParametersWinIniFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemParametersWinIniFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SystemParametersWinIniFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SystemParametersWinIniFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SystemParametersWinIniFlags.None">**None**</td><td>0</td><td>None.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SystemParametersWinIniFlags.UpdateIniFile">**UpdateIniFile**</td><td>1</td><td>Writes the new system-wide parameter setting to the user profile.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SystemParametersWinIniFlags.SendChange">**SendChange**</td><td>2</td><td>Broadcasts the `WM_SETTINGCHANGE` message after updating the user profile.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SystemParametersWinIniFlags.SendWinIniChange">**SendWinIniChange**</td><td>3</td><td>Same as SendChange.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms724947(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms724947(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />