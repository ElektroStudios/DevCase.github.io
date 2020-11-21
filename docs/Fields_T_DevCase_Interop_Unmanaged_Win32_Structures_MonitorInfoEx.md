# MonitorInfoEx Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx">MonitorInfoEx</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_Bounds">Bounds</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that specifies the display monitor rectangle, expressed in virtual-screen coordinates. 

 Note that if the monitor is not the primary display monitor, some of the rectangle's coordinates may be negative values.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_DeviceName">DeviceName</a></td><td>
A string that specifies the device name of the monitor being used. 

 Most applications have no use for a display monitor name, and so can save some bytes by using a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfo">MonitorInfo</a> structure.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_Flags">Flags</a></td><td>
The attributes of the display monitor.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_SizeOfStruct">SizeOfStruct</a></td><td>
The size, in bytes, of the structure. 

 This member must be set to `Marshal.SizeOf(Of MonitorInfoEx)` before calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMonitorInfo">GetMonitorInfo(IntPtr, MonitorInfo)</a> function. Doing so lets the function determine the type of structure you are passing to it.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_WorkingArea">WorkingArea</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that specifies the work area rectangle of the display monitor that can be used by applications, expressed in virtual-screen coordinates. 

 Windows uses this rectangle to maximize an application on the monitor. The rest of the area in <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_Bounds">Bounds</a> contains system windows such as the task bar and side bars. 

 Note that if the monitor is not the primary display monitor, some of the rectangle's coordinates may be negative values.</td></tr></table>&nbsp;
<a href="#monitorinfoex-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx">MonitorInfoEx Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />