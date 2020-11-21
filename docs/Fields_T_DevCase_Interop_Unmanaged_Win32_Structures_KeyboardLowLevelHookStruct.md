# KeyboardLowLevelHookStruct Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardLowLevelHookStruct">KeyboardLowLevelHookStruct</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardLowLevelHookStruct_ExtraInfo">ExtraInfo</a></td><td>
Additional information associated with the message.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardLowLevelHookStruct_Flags">Flags</a></td><td>
The extended-key flag, event-injected flags, context code, and transition-state flag. 

 This member is specified as follows. An application can use the following values to test the keystroke flags. 

 Testing `LLKHF_INJECTED` (bit 4) will tell you whether the event was injected. If it was, then testing `LLKHF_LOWER_IL_INJECTED` (bit 1) will tell you whether or not the event was injected from a process running at lower integrity level.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardLowLevelHookStruct_ScanCode">ScanCode</a></td><td>
A hardware scan code for the key.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardLowLevelHookStruct_Time">Time</a></td><td>
The time stamp for this message, equivalent to what `GetMessageTime` would return for this message.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardLowLevelHookStruct_VkCode">VkCode</a></td><td>
A virtual-key code. 

 The code must be a value in the range `1` to `254`.</td></tr></table>&nbsp;
<a href="#keyboardlowlevelhookstruct-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardLowLevelHookStruct">KeyboardLowLevelHookStruct Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />