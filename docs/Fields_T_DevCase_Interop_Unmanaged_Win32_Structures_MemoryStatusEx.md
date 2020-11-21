# MemoryStatusEx Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx">MemoryStatusEx</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_ExtendedVirtualAvailable">ExtendedVirtualAvailable</a></td><td>
Size of unreserved and uncommitted memory in the extended portion of the virtual address space of the calling process, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_MemoryLoad">MemoryLoad</a></td><td>
Number between 0 and 100 that specifies the approximate percentage of physical memory that is in use 

 (0 indicates no memory use and 100 indicates full memory use).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PageFileAvailable">PageFileAvailable</a></td><td>
Size of available memory to commit, in bytes. 

 The limit is <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PageFileTotal">PageFileTotal</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PageFileTotal">PageFileTotal</a></td><td>
Size of the committed memory limit, in bytes. 

 This is physical memory plus the size of the page file, minus a small overhead.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PhysicalAvailable">PhysicalAvailable</a></td><td>
Size of physical memory available, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PhysicalTotal">PhysicalTotal</a></td><td>
Total size of physical memory, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of MemoryStatusEx)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_VirtualAvailable">VirtualAvailable</a></td><td>
Size of unreserved and uncommitted memory in the user mode portion of the virtual address space of the calling process, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_VirtualTotal">VirtualTotal</a></td><td>
Total size of the user mode portion of the virtual address space of the calling process, in bytes.</td></tr></table>&nbsp;
<a href="#memorystatusex-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx">MemoryStatusEx Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />