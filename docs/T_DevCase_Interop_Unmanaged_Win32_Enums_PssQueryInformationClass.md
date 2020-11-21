# PssQueryInformationClass Enumeration
 

Specifies what information <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PssQuerySnapshot">PssQuerySnapshot(IntPtr, PssQueryInformationClass, IntPtr, UInt32)</a> function returns.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum PssQueryInformationClass
```

**VB**<br />
``` VB
Public Enumeration PssQueryInformationClass
```

**VB Usage**<br />
``` VB Usage
Dim instance As PssQueryInformationClass
```

**C++**<br />
``` C++
public enum class PssQueryInformationClass
```

**F#**<br />
``` F#
type PssQueryInformationClass
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssQueryInformationClass.ProcessInformarion">**ProcessInformarion**</td><td>0</td><td>Returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation">PssProcessInformation</a> structure, with information about the original process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssQueryInformationClass.VirtualAddressCloneInformation">**VirtualAddressCloneInformation**</td><td>1</td><td>Returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssVirtualAddressCloneInformation">PssVirtualAddressCloneInformation</a> structure, with a handle to the VA clone.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssQueryInformationClass.AuxiliaryPagesInformation">**AuxiliaryPagesInformation**</td><td>2</td><td>Returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssAuxiliaryPagesInformation">PssAuxiliaryPagesInformation</a> structure, which contains the count of auxiliary pages captured.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssQueryInformationClass.VirtualAddressSpaceInformation">**VirtualAddressSpaceInformation**</td><td>3</td><td>Returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssVirtualAddressSpaceInformation">PssVirtualAddressSpaceInformation</a> structure, which contains the count of regions captured.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssQueryInformationClass.HandleInformation">**HandleInformation**</td><td>4</td><td>Returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssHandleInformation">PssHandleInformation</a> structure, which contains the count of handles captured.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssQueryInformationClass.ThreadInformation">**ThreadInformation**</td><td>5</td><td>Returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssThreadInformation">PssThreadInformation</a> structure, which contains the count of threads captured.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssQueryInformationClass.HandleTraceInformation">**HandleTraceInformation**</td><td>6</td><td>Returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssHandleTraceInformation">PssHandleTraceInformation</a> structure, which contains a handle to the handle trace section, and its size.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssQueryInformationClass.PerformanceCounters">**PerformanceCounters**</td><td>7</td><td>Returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters">PssPerformanceCounters</a> structure, which contains various performance counters.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ne-processsnapshot-pss_query_information_class" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ne-processsnapshot-pss_query_information_class</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />