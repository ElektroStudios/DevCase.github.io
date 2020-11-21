# MemoryState Enumeration
 

Specifies the state of the pages in the memory region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MemoryState
```

**VB**<br />
``` VB
Public Enumeration MemoryState
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryState
```

**C++**<br />
``` C++
public enum class MemoryState
```

**F#**<br />
``` F#
type MemoryState
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryState.Commit">**Commit**</td><td>4096</td><td>Indicates committed pages for which physical storage has been allocated, either in memory or in the paging file on disk.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryState.Free">**Free**</td><td>65536</td><td>Indicates free pages not accessible to the calling process and available to be allocated. 

 For free pages, the information in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_AllocationBase">AllocationBase</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_AllocationProtect">AllocationProtect</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_Protect">Protect</a>, and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_Type">Type</a> members is undefined.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryState.Reserve">**Reserve**</td><td>8192</td><td>Indicates reserved pages where a range of the process's virtual address space is reserved without any physical storage being allocated. 

 For reserved pages, the information in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_Protect">Protect</a> member is undefined.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680386(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680386(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />