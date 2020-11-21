# ScrollInfo Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo">ScrollInfo</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Mask">Mask</a></td><td>
The scroll bar parameters to set or retrieve.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Max">Max</a></td><td>
The maximum scrolling position.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Min">Min</a></td><td>
The minimum scrolling position.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Page">Page</a></td><td>
The page size, in device units. 

 A scroll bar uses this value to determine the appropriate size of the proportional scroll box.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Pos">Pos</a></td><td>
The position of the scroll box.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of ScrollInfo)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_TrackPos">TrackPos</a></td><td>
The immediate position of a scroll box that the user is dragging. 

 An application can retrieve this value while processing the `SB_THUMBTRACK` request code. 

 An application cannot set the immediate scroll position; the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetScrollInfo">SetScrollInfo(IntPtr, ScrollBarOrientation, ScrollInfo, Boolean)</a> function ignores this member.</td></tr></table>&nbsp;
<a href="#scrollinfo-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo">ScrollInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />