# KeyboardInput Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput">KeyboardInput</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_ExtraInfo">ExtraInfo</a></td><td>
An additional value associated with the keystroke. 

 Use the `GetMessageExtraInfo` function to obtain this information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Flags">Flags</a></td><td>
Specifies various aspects of a keystroke.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_ScanCode">ScanCode</a></td><td>
A hardware scan code for the key. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeyboardInputFlags">Unicode</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_ScanCode">ScanCode</a> specifies a Unicode character which is to be sent to the foreground application.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Time">Time</a></td><td>
The time stamp for the event, in milliseconds. 

 If this parameter is `0`, the system will provide its own time stamp.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_VirtualKey">VirtualKey</a></td><td>
A virtual-key code. 

 The code must be a value in the range `1` to `254`. 

 If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Flags">Flags</a> member specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeyboardInputFlags">Unicode</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_VirtualKey">VirtualKey</a> must be `0`.</td></tr></table>&nbsp;
<a href="#keyboardinput-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput">KeyboardInput Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />