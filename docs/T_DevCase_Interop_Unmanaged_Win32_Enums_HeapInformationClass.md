# HeapInformationClass Enumeration
 

Specifies a class of heap information to be set or retrieved.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum HeapInformationClass
```

**VB**<br />
``` VB
Public Enumeration HeapInformationClass
```

**VB Usage**<br />
``` VB Usage
Dim instance As HeapInformationClass
```

**C++**<br />
``` C++
public enum class HeapInformationClass
```

**F#**<br />
``` F#
type HeapInformationClass
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapInformationClass.CompatibilityInformation">**CompatibilityInformation**</td><td>0</td><td>Enables heap features. 

 The available features vary based on operating system. 

 The heap features depends on the `heapInformation` parameter in the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapQueryInformation">HeapQueryInformation(IntPtr, HeapInformationClass, IntPtr, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapSetInformation">HeapSetInformation(IntPtr, HeapInformationClass, IntPtr, UInt32)</a> functions.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapInformationClass.EnableTerminationOnCorruption">**EnableTerminationOnCorruption**</td><td>1</td><td>Enables the terminate-on-corruption feature. 

 If the heap manager detects an error in any heap used by the process, it calls the Windows Error Reporting (WER) service and terminates the process. 

 After a process enables this feature, it cannot be disabled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapInformationClass.OptimizeResources">**OptimizeResources**</td><td>3</td><td>If <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapSetInformation">HeapSetInformation(IntPtr, HeapInformationClass, IntPtr, UInt32)</a> is called with `hHeap` parameter set to Zero, then all heaps in the process with a low-fragmentation heap (LFH) will have their caches optimized, and the memory will be decommitted if possible. 

 If a heap pointer is supplied in `hHeap` parameter, then only that heap will be optimized. 

 Note that the HEAP_OPTIMIZE_RESOURCES_INFORMATION structure passed in `heapInformation` parameter must be properly initialized.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapsetinformation" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapsetinformation</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />