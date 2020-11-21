# PssCaptureFlags Enumeration
 

Specifies what information <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PssCaptureSnapshot">PssCaptureSnapshot(IntPtr, PssCaptureFlags, UInt32, IntPtr)</a> function captures.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum PssCaptureFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration PssCaptureFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As PssCaptureFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class PssCaptureFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type PssCaptureFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.None">**None**</td><td>0</td><td>Capture nothing.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureVirtualAddressClone">**CaptureVirtualAddressClone**</td><td>1</td><td>Capture a snapshot of all cloneable pages in the process. 

 The clone includes all MEM_PRIVATE regions, as well as all sections (MEM_MAPPED and MEM_IMAGE) that are shareable. 

 All Win32 sections created via CreateFileMapping function are shareable.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.Reserved_00000002">**Reserved_00000002**</td><td>2</td><td>Reserved by the system. Do not use this flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureHandles">**CaptureHandles**</td><td>4</td><td>Capture the handle table (handle values only).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureHandleNameInformation">**CaptureHandleNameInformation**</td><td>8</td><td>Capture name information for each handle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureHandleBasicInformation">**CaptureHandleBasicInformation**</td><td>16</td><td>Capture basic handle information such as HandleCount, PointerCount, GrantedAccess, etc.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureHandleTypeSpecificInformation">**CaptureHandleTypeSpecificInformation**</td><td>32</td><td>Capture type-specific information for supported object types: Process, Thread, Event, Mutant, Section.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureHandleTrace">**CaptureHandleTrace**</td><td>64</td><td>Capture the handle tracing table.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureThreads">**CaptureThreads**</td><td>128</td><td>Capture thread information (IDs only).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureThreadContext">**CaptureThreadContext**</td><td>256</td><td>Capture the context for each thread.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureThreadContextExtended">**CaptureThreadContextExtended**</td><td>512</td><td>Capture extended context for each thread (e.g. ContextXSTATE).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.Reserved_00000400">**Reserved_00000400**</td><td>1024</td><td>Reserved by the system. Do not use this flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureVirtualAddressSpace">**CaptureVirtualAddressSpace**</td><td>2048</td><td>Capture a snapshot of the virtual address space. 

 The Virtual Address (VA) space is captured as an array of MEMORY_BASIC_INFORMATION structures. 

 This flag does not capture the contents of the pages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureVirtualAddressSpaceSectionInformation">**CaptureVirtualAddressSpaceSectionInformation**</td><td>4096</td><td>For MEM_IMAGE and MEM_MAPPED regions, dumps the path to the file backing the sections (identical to what GetMappedFileName returns). 

 For MEM_IMAGE regions, also dumps: The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a> access right is required on the process handle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CaptureIptTrace">**CaptureIptTrace**</td><td>8192</td><td>(missing documentation).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CreateBreakawayOptional">**CreateBreakawayOptional**</td><td>67108864</td><td>The breakaway is optional. 

 If the clone process fails to create as a breakaway, then it is created still inside the job. 

 This flag must be specified in combination with either CreateForceBreakaway and/or CreateBreakaway.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CreateBreakaway">**CreateBreakaway**</td><td>134217728</td><td>The clone is broken away from the parent process' job. 

 This is equivalent to CreateProcess flag CREATE_BREAKAWAY_FROM_JOB.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CreateForceBreakaway">**CreateForceBreakaway**</td><td>268435456</td><td>The clone is forcefully broken away the parent process's job. 

 This is only allowed for Tcb-privileged callers.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CreateUseVmAllocations">**CreateUseVmAllocations**</td><td>536870912</td><td>The facility should not use the process heap for any persistent or transient allocations. 

 The use of the heap may be undesirable in certain contexts such as creation of snapshots in the exception reporting path (where the heap may be corrupted).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CreateMeasurePerformance">**CreateMeasurePerformance**</td><td>1073741824</td><td>Measure performance of the facility. 

 Performance counters can be retrieved via <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PssQuerySnapshot">PssQuerySnapshot(IntPtr, PssQueryInformationClass, IntPtr, UInt32)</a> function with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PssQueryInformationClass">PerformanceCounters</a> information class.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags.CreateReleaseSection">**CreateReleaseSection**</td><td>2147483648</td><td>The virtual address (VA) clone process does not hold a reference to the underlying image. 

 This will cause functions such as QueryFullProcessImageName to fail on the Virtual Address (VA) clone process. 

 This flag has no effect unless CaptureVirtualAddressClone is specified.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processsnapshot/ne-processsnapshot-pss_capture_flags" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processsnapshot/ne-processsnapshot-pss_capture_flags</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />