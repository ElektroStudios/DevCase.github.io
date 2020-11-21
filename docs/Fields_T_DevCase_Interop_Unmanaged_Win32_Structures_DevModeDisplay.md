# DevModeDisplay Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevModeDisplay">DevModeDisplay</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModeDisplay_DisplayFixedOutput">DisplayFixedOutput</a></td><td>
For fixed-resolution display devices only, how the display presents a low-resolution mode on a higher-resolution display. 

 For example, if a display device's resolution is fixed at 1024 x 768 pixels but its mode is set to 640x480 pixels, the device can either display a 640x480 image somewhere in the interior of the 1024x768 screen space or stretch the 640x480 image to fill the larger screen space. 

 If <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeFields">DisplayFixedOutput</a> is not set, this member must be zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModeDisplay_DisplayOrientation">DisplayOrientation</a></td><td>
For display devices only, the orientation at which images should be presented. 

 If <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeFields">DisplayOrientation</a> is not set, this member must be <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeDisplayOrientation">Default</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModeDisplay_Position">Position</a></td><td>
For display devices only, a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> struct that indicates the positional coordinates of the display device in reference to the desktop area. 

 The primary display device is always located at coordinates (0,0).</td></tr></table>&nbsp;
<a href="#devmodedisplay-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevModeDisplay">DevModeDisplay Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />