# MemoryFreeType Enumeration
 

Specifies the type of a memory free operation.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MemoryFreeType
```

**VB**<br />
``` VB
Public Enumeration MemoryFreeType
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryFreeType
```

**C++**<br />
``` C++
public enum class MemoryFreeType
```

**F#**<br />
``` F#
type MemoryFreeType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryFreeType.Decommit">**Decommit**</td><td>16384</td><td>Decommits the specified region of committed pages. 

 After the operation, the pages are in the reserved state. 

 The function does not fail if you attempt to decommit an uncommitted page. This means that you can decommit a range of pages without first determining the current commitment state. 

 When using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> fucntion, the Decommit value is not supported when the `address` parameter provides the base address for an enclave.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryFreeType.Release">**Release**</td><td>32768</td><td>Releases the specified region of pages. 

 After this operation, the pages are in the free state. 

 When using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> fucntion, if you specify this value, `size` parameter must be Zero, and `address` parameter must point to the base address returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> fucntion when the region is reserved. The function fails if either of these conditions is not met. 

 If any pages in the region are committed currently, the function first decommits, and then releases them. 

 The function does not fail if you attempt to release pages that are in different states, some reserved and some committed. This means that you can release a range of pages without first determining the current commitment state.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366892%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366892%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />