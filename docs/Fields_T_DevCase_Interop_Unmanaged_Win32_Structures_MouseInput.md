# MouseInput Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput">MouseInput</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_ExtraInfo">ExtraInfo</a></td><td>
An additional value associated with the mouse event. 

 An application calls `GetMessageExtraInfo` to obtain this extra information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Flags">Flags</a></td><td>
A set of bit flags that specify various aspects of mouse motion and button clicks. 

 The bit flags that specify mouse button status are set to indicate changes in status, not ongoing conditions. 

 For example, if the left mouse button is pressed and held down, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">LeftDown</a> is set when the left button is first pressed, but not for subsequent motions. 

 Similarly, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">LeftUp</a> is set only when the button is first released. 

 You cannot specify both the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">Wheel</a> flag and either <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">XDown</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">XUp</a> flags simultaneously in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Flags">Flags</a> parameter, because they both require use of the 'mouseData' field.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_MouseData">MouseData</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Flags">Flags</a> contains <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">Wheel</a>, then <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_MouseData">MouseData</a> specifies the amount of wheel movement. 

 A positive value indicates that the wheel was rotated forward, away from the user. 

 a negative value indicates that the wheel was rotated backward, toward the user. One wheel click is defined as `WHEEL_DELTA`, which is `120`. If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Flags">Flags</a> does not contain <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">Wheel</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">XDown</a>, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseInputFlags">XUp</a>, then <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_MouseData">MouseData</a> should be `0`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Time">Time</a></td><td>
The time stamp for the event, in milliseconds. 

 If this parameter is `0`, the system will provide its own time stamp.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_X">X</a></td><td>
The absolute position of the mouse, or the amount of motion since the last mouse event was generated, depending on the value of the flags member. 

 Absolute data is specified as the 'x' coordinate of the mouse; relative data is specified as the number of pixels moved.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Y">Y</a></td><td>
The absolute position of the mouse, or the amount of motion since the last mouse event was generated, depending on the value of the flags member. 

 Absolute data is specified as the 'y' coordinate of the mouse; relative data is specified as the number of pixels moved.</td></tr></table>&nbsp;
<a href="#mouseinput-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput">MouseInput Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />