# ApplicationRestartFlags Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegisterApplicationRestart">RegisterApplicationRestart(String, ApplicationRestartFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ApplicationRestartFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ApplicationRestartFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ApplicationRestartFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ApplicationRestartFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ApplicationRestartFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ApplicationRestartFlags.NoCrash">**NoCrash**</td><td>1</td><td>Do not restart the process if it terminates due to an unhandled exception.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ApplicationRestartFlags.NoHang">**NoHang**</td><td>2</td><td>Do not restart the process if it terminates due to the application not responding.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ApplicationRestartFlags.NoPatch">**NoPatch**</td><td>4</td><td>Do not restart the process if it terminates due to the installation of an update.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ApplicationRestartFlags.NoReboot">**NoReboot**</td><td>8</td><td>Do not restart the process if the computer is restarted as the result of an update.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-registerapplicationrestart" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-registerapplicationrestart</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />