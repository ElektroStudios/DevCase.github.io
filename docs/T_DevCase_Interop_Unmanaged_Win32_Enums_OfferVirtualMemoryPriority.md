# OfferVirtualMemoryPriority Enumeration
 

Specifies how important a offered virtual memory is to the application. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OfferVirtualMemory">OfferVirtualMemory(IntPtr, IntPtr, OfferVirtualMemoryPriority)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum OfferVirtualMemoryPriority
```

**VB**<br />
``` VB
Public Enumeration OfferVirtualMemoryPriority
```

**VB Usage**<br />
``` VB Usage
Dim instance As OfferVirtualMemoryPriority
```

**C++**<br />
``` C++
public enum class OfferVirtualMemoryPriority
```

**F#**<br />
``` F#
type OfferVirtualMemoryPriority
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OfferVirtualMemoryPriority.VmOfferPriorityVeryLow">**VmOfferPriorityVeryLow**</td><td>4096</td><td>The offered memory Is very low priority, and should be the first discarded.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OfferVirtualMemoryPriority.VmOfferPriorityLow">**VmOfferPriorityLow**</td><td>8192</td><td>The offered memory Is low priority.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OfferVirtualMemoryPriority.VmOfferPriorityBelowNormal">**VmOfferPriorityBelowNormal**</td><td>8192</td><td>The offered memory Is below normal priority.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OfferVirtualMemoryPriority.VmOfferPriorityNormal">**VmOfferPriorityNormal**</td><td>8192</td><td>The offered memory Is of normal priority to the application, and should be the last discarded.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-offervirtualmemory" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-offervirtualmemory</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />