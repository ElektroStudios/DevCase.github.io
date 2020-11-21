# WerFaultReporting Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WerGetFlags">WerGetFlags(IntPtr, WerFaultReporting)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WerSetFlags">WerSetFlags(WerFaultReporting)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum WerFaultReporting
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration WerFaultReporting
```

**VB Usage**<br />
``` VB Usage
Dim instance As WerFaultReporting
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class WerFaultReporting
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type WerFaultReporting
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.NoHeap">**NoHeap**</td><td>1</td><td>Do not collect heap information in the event of an application crash or non-response.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.Queue">**Queue**</td><td>2</td><td>Queue critical reports for the specified process. This does not show any UI.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.DisableThreadSuspension">**DisableThreadSuspension**</td><td>4</td><td>Do not suspend the process threads before reporting the error.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.QueueUpload">**QueueUpload**</td><td>8</td><td>Queue critical reports and upload from the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.AlwaysShowUI">**AlwaysShowUI**</td><td>16</td><td>Always show error reporting UI for this process. This is applicable for interactive applications only.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.NoUI">**NoUI**</td><td>32</td><td>(Undocumented)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.NoHeapOnQueue">**NoHeapOnQueue**</td><td>64</td><td>(Undocumented)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.DisableSnapshotCrash">**DisableSnapshotCrash**</td><td>128</td><td>(Undocumented)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.DisableSnapshotHang">**DisableSnapshotHang**</td><td>256</td><td>(Undocumented)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.Critical">**Critical**</td><td>512</td><td>(Undocumented)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting.Durable">**Durable**</td><td>1024</td><td>(Undocumented)</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-wergetflags" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-wergetflags</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />