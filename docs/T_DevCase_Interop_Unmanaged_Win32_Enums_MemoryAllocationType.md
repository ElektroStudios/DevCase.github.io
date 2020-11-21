# MemoryAllocationType Enumeration
 

Specifies the type of memory allocation operation.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MemoryAllocationType
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MemoryAllocationType
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryAllocationType
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MemoryAllocationType
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MemoryAllocationType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType.Default">**Default**</td><td>0</td><td>This meaning of this value depends on the function on which it is used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType.Commit">**Commit**</td><td>4096</td><td>Allocates memory charges (from the overall size of memory and the paging files on disk) for the specified reserved memory pages. 

 The function also guarantees that when the caller later initially accesses the memory, the contents will be zero. 

 Actual physical pages are not allocated unless/until the virtual addresses are actually accessed. 

 To reserve and commit pages in one step, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> with Commit and Reserve. 

 Attempting to commit a specific address range by specifying Commit without Reserve and a non-Zero`address` fails unless the entire range has already been reserved. The resulting error code is `ERROR_INVALID_ADDRESS`. 

 An attempt to commit a page that is already committed does not cause the function to fail. This means that you can commit pages without first determining the current commitment state of each page. 

 If `address` specifies an address within an enclave, `allocationType` must be Commit.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType.Reserve">**Reserve**</td><td>8192</td><td>Reserves a range of the process's virtual address space without allocating any actual physical storage in memory or in the paging file on disk. 

 You commit reserved pages by calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> again with Commit. 

 To reserve and commit pages in one step, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> with Commit and Reserve. 

 Other memory allocation functions, such as `malloc` and `LocalAlloc`, cannot use reserved memory until it has been released.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType.Reset">**Reset**</td><td>524288</td><td>When calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function, indicates that data in the memory range specified by `address` and `size` parameters is no longer of interest. 

 The pages should not be read from or written to the paging file. However, the memory block will be used again later, so it should not be decommitted. 

 This value cannot be used with any other value. 

 Using this value does not guarantee that the range operated on with Reset will contain zeros. 

 If you want the range to contain zeros, decommit the memory and then recommit it. 

 When you use Reset, the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function ignores the value of `protection` parameter. However, you must still set fProtect to a valid protection value, such as <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">NoAccess</a>. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function returns an error if you use Reset and the range of memory is mapped to a file. 

 A shared view is only acceptable if it is mapped to a paging file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType.ResetUndo">**ResetUndo**</td><td>16777216</td><td>ResetUndo should only be called on an address range to which Reset was successfully applied earlier. 

 When calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function, it indicates that the data in the specified memory range specified by `address` and `size` parameters is of interest to the caller and attempts to reverse the effects of Reset. 

 If the function succeeds, that means all data in the specified address range is intact. 

 If the function fails, at least some of the data in the address range has been replaced with zeroes. 

 This value cannot be used with any other value. 

 If ResetUndo is called on an address range which was not Reset earlier, the behavior is undefined. 

 When you specify Reset, the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function ignores the value of `protection` parameter. However, you must still set `protection` parameter to a valid protection value, such as <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">NoAccess</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType.Physical">**Physical**</td><td>4194304</td><td>Reserves an address range that can be used to map `Address Windowing Extensions` (`AWE`) pages. 

 This value must be used with Reserve and no other values.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType.TopDown">**TopDown**</td><td>1048576</td><td>Allocates memory at the highest possible address. 

 This can be slower than regular allocations, especially when there are many allocations.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType.LargePages">**LargePages**</td><td>536870912</td><td>Allocates memory using `large page support`. 

 The size and alignment must be a multiple of the large-page minimum. 

 To obtain this value, use the `GetLargePageMinimum` function.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366890%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366890%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />