# PssProcessFlags Enumeration
 

Flags that describe a process in a process snapshot (pss). 

 Used by <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_Flags">Flags</a> member.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum PssProcessFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration PssProcessFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As PssProcessFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class PssProcessFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type PssProcessFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssProcessFlags.None">**None**</td><td>0</td><td>No flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssProcessFlags.Protected">**Protected**</td><td>1</td><td>The process is protected.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssProcessFlags.WoW64">**WoW64**</td><td>2</td><td>The process is a 32-bit process running on a 64-bit native OS.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssProcessFlags.Reserved_03">**Reserved_03**</td><td>4</td><td>Reserved by the system Do not use.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssProcessFlags.Reserved_04">**Reserved_04**</td><td>8</td><td>Reserved by the system Do not use.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssProcessFlags.Frozen">**Frozen**</td><td>16</td><td>The process is frozen; for example, a debugger is attached and broken into the process or a store process is suspended by a lifetime management service.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ne-processsnapshot-pss_duplicate_flags" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ne-processsnapshot-pss_duplicate_flags</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />