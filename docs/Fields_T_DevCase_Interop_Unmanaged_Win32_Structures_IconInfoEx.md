# IconInfoEx Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx">IconInfoEx</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx_Color">Color</a></td><td>
A handle to the icon color bitmap. 

 This member can be optional if this structure defines a black and white icon. 

 The `AND` bitmask of <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo_Mask">Mask</a> member is applied with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TernaryRasterOperations">SrcAnd</a> flag to the destination; subsequently, the color bitmap is applied (using `XOR`) to the destination by using the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TernaryRasterOperations">SrcInvert</a> flag.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx_IsIcon">IsIcon</a></td><td>
Specifies whether this structure defines an icon or a cursor. 

 A value of `true` (`True` in Visual Basic) specifies an icon; `false` (`False` in Visual Basic) specifies a cursor.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx_Mask">Mask</a></td><td>
The icon bitmask bitmap. 

 If this structure defines a black and white icon, this bitmask is formatted so that the upper half is the icon `AND` bitmask and the lower half is the icon `XOR` bitmask. 

 Under this condition, the height should be an even multiple of two. 

 If this structure defines a color icon, this mask only defines the `AND` bitmask of the icon.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx_ModuleName">ModuleName</a></td><td>
The fully qualified path of the module.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx_ResourceID">ResourceID</a></td><td>
The icon or cursor resource bits. 

 These bits are typically loaded by calls to the LookupIconIdFromDirectoryEx and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadResource">LoadResource(SafeModuleHandle, IntPtr)</a> functions.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx_ResourceName">ResourceName</a></td><td>
The fully qualified path of the resource.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of IconInfoEx)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx_X">X</a></td><td>
The x-coordinate of a cursor's hot spot. 

 If this structure defines an icon, the hot spot is always in the center of the icon, and this member is ignored.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx_Y">Y</a></td><td>
The y-coordinate of the cursor's hot spot. 

 If this structure defines an icon, the hot spot is always in the center of the icon, and this member is ignored</td></tr></table>&nbsp;
<a href="#iconinfoex-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx">IconInfoEx Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />