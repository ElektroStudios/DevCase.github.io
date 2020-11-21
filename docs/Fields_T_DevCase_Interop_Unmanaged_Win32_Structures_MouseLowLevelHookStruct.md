# MouseLowLevelHookStruct Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct">MouseLowLevelHookStruct</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_ExtraInfo">ExtraInfo</a></td><td>
Additional information associated with the message.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_Flags">Flags</a></td><td>
The extended-key flag, event-injected flags, context code, and transition-state flag. 

 This member is specified as follows. An application can use the following values to test the mouse flags. 

 Testing `LLKHF_INJECTED` (bit 4) will tell you whether the event was injected. If it was, then testing `LLKHF_LOWER_IL_INJECTED` (bit 1) will tell you whether or not the event was injected from a process running at lower integrity level.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_MouseData">MouseData</a></td><td>
If the message is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseWheel</a>, the high-order word of this member is the wheel delta. 

 ( The low-order word is reserved. ) 

 A positive value indicates that the wheel was rotated forward, away from the user; a negative value indicates that the wheel was rotated backward, toward the user. 

 One wheel click is defined as `WHEEL_DELTA`, which is `120`. 





 If the message is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_XButtonDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_XButtonUp</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_XButtonDblClk</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcXButtonDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcXButtonUp</a>, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcXButtonDblClk</a>, the high-order word specifies which X button was pressed or released, and the low-order word is reserved. 

 This value can be one or more of the following values. Otherwise, mouseData is not used.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_Point">Point</a></td><td>
The x- and y-coordinates of the cursor, in screen coordinates.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_Time">Time</a></td><td>
The time stamp for this message, equivalent to what `GetMessageTime` would return for this message.</td></tr></table>&nbsp;
<a href="#mouselowlevelhookstruct-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct">MouseLowLevelHookStruct Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />