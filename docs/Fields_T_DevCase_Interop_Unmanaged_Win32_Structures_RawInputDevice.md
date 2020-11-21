# RawInputDevice Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_Flags">Flags</a></td><td>
Mode flag that specifies how to interpret the information provided by <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_UsagePage">UsagePage</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_Usage">Usage</a>. 

 It can be zero (the default) or one of the following values. 

 By default, the operating system sends raw input from devices with the specified top level collection (TLC) to the registered application as long as it has the window focus.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_HwndTarget">HwndTarget</a></td><td>
A handle to the target window. 

 If this value is Zero, it follows the keyboard focus.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_Usage">Usage</a></td><td>
Top level collection Usage for the raw input device.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_UsagePage">UsagePage</a></td><td>
Top level collection Usage page for the raw input device.</td></tr></table>&nbsp;
<a href="#rawinputdevice-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />