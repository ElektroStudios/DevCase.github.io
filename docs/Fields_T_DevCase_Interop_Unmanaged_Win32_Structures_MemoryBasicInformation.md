# MemoryBasicInformation Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation">MemoryBasicInformation</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_AllocationBase">AllocationBase</a></td><td>
A pointer to the base address of a range of pages allocated by the VirtualAlloc function. 

 The page pointed to by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_BaseAddress">BaseAddress</a> member is contained within this allocation range.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_AllocationProtect">AllocationProtect</a></td><td>
The memory protection option when the region was initially allocated. 

 This member can be one of the memory protection constants or 0 if the caller does not have access.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_BaseAddress">BaseAddress</a></td><td>
A pointer to the base address of the region of pages.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_Protect">Protect</a></td><td>
The access protection of the pages in the region. 

 This member is one of the values listed for the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_AllocationProtect">AllocationProtect</a> member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_RegionSize">RegionSize</a></td><td>
The size of the region beginning at the base address in which all pages have identical attributes, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_State">State</a></td><td>
The state of the pages in the region.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_Type">Type</a></td><td>
The type of pages in the region.</td></tr></table>&nbsp;
<a href="#memorybasicinformation-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation">MemoryBasicInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />