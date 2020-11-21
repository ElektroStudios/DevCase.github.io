# ISharedBitmap Methods
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_Detach">Detach</a></td><td>
Retrieves the bitmap contained in an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object, and returns a copy if the contained bitmap resides in shared memory. 

 After calling this method the bitmap is no longer associated with this <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object and you cannot call <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_GetSharedBitmap">GetSharedBitmap(IntPtr)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_Detach">Detach(IntPtr)</a> on it again.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_GetFormat">GetFormat</a></td><td>
Retrieves the alpha type of the bitmap image..</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_GetSharedBitmap">GetSharedBitmap</a></td><td>
Retrieves the bitmap contained in an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_GetSize">GetSize</a></td><td>
Retrieves the size of the bitmap contained in an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_InitializeBitmap">InitializeBitmap</a></td><td>
Initializes a new <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object with a given bitmap.</td></tr></table>&nbsp;
<a href="#isharedbitmap-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />