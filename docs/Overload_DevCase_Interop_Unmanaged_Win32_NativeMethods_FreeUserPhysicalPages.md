# NativeMethods.FreeUserPhysicalPages Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FreeUserPhysicalPages">FreeUserPhysicalPages(IntPtr, IntPtr, IntPtr)</a></td><td>
Frees physical memory pages that are allocated previously by using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocateUserPhysicalPages">AllocateUserPhysicalPages(IntPtr, IntPtr, IntPtr)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocateUserPhysicalPagesNuma">AllocateUserPhysicalPagesNuma(IntPtr, IntPtr, IntPtr, UInt32)</a>. 

 If any of these pages are currently mapped in the Address Windowing Extensions (AWE) region, they are automatically unmapped by this call. 

 This does not affect the virtual address space that is occupied by a specified Address Windowing Extensions (AWE) region.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FreeUserPhysicalPages_1">FreeUserPhysicalPages(IntPtr, UIntPtr, UIntPtr)</a></td><td>
Frees physical memory pages that are allocated previously by using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocateUserPhysicalPages">AllocateUserPhysicalPages(IntPtr, IntPtr, IntPtr)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocateUserPhysicalPagesNuma">AllocateUserPhysicalPagesNuma(IntPtr, IntPtr, IntPtr, UInt32)</a>. 

 If any of these pages are currently mapped in the Address Windowing Extensions (AWE) region, they are automatically unmapped by this call. 

 This does not affect the virtual address space that is occupied by a specified Address Windowing Extensions (AWE) region.</td></tr></table>&nbsp;
<a href="#nativemethods.freeuserphysicalpages-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />