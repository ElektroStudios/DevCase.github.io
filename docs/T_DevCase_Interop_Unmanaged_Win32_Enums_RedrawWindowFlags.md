# RedrawWindowFlags Enumeration
 

Specifies how a window must be redrawn by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RedrawWindow">RedrawWindow(IntPtr, NativeRectangle, IntPtr, RedrawWindowFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum RedrawWindowFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration RedrawWindowFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As RedrawWindowFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class RedrawWindowFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type RedrawWindowFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.Invalidate">**Invalidate**</td><td>1</td><td>Invalidates the rectangle or region that you specify in `lprcUpdate` or `hrgnUpdate` parameters. 

 You can set only one of these parameters to a non-Zero value. If both are Zero, Invalidate invalidates the entire window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.InternalPaint">**InternalPaint**</td><td>2</td><td>Causes the OS to post a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message to the window regardless of whether a portion of the window is invalid.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.Erase">**Erase**</td><td>4</td><td>Causes the window to receive a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_EraseBkgnd</a> message when the window is repainted. 

 Specify this value in combination with the Invalidate value; otherwise, Erase has no effect.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.Validate">**Validate**</td><td>8</td><td>Validates the rectangle or region that you specify in `lprcUpdate` or `hrgnUpdate` parameters. 

 You can set only one of these parameters to a non-Zero value. If both are Zero, Validate validates the entire window. 

 This value does not affect internal <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.NoInternalPaint">**NoInternalPaint**</td><td>16</td><td>Suppresses any pending internal <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> messages. 

 This flag does not affect <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> messages resulting from a non-NULL update area.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.NoErase">**NoErase**</td><td>32</td><td>Suppresses any pending <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_EraseBkgnd</a> messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.NoChildren">**NoChildren**</td><td>64</td><td>Excludes child windows, if any, from the repainting operation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.AllChildren">**AllChildren**</td><td>128</td><td>Includes child windows, if any, in the repainting operation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.UpdateNow">**UpdateNow**</td><td>256</td><td>Causes the affected windows, which you specify by setting the AllChildren and NoChildren values, to receive <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_EraseBkgnd</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> messages before the RedrawWindow returns, if necessary.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.EraseNow">**EraseNow**</td><td>512</td><td>Causes the affected windows, which you specify by setting the AllChildren and NoChildren values, to receive <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_EraseBkgnd</a> messages before <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RedrawWindow">RedrawWindow(IntPtr, NativeRectangle, IntPtr, RedrawWindowFlags)</a> returns, if necessary. 

 The affected windows receive <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> messages at the ordinary time.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.Frame">**Frame**</td><td>1024</td><td>Causes any part of the non-client area of the window that intersects the update region to receive a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcPaint</a> message. 

 The Invalidate flag must also be specified; otherwise, Frame has no effect. 

 The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcPaint</a> message is typically not sent during the execution of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RedrawWindow">RedrawWindow(IntPtr, NativeRectangle, IntPtr, RedrawWindowFlags)</a> unless either UpdateNow or EraseNow is specified.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags.NoFrame">**NoFrame**</td><td>2048</td><td>Suppresses any pending <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcPaint</a> messages. 

 This flag must be used with Validate and is typically used with NoChildren. 

NoFrame should be used with care, as it could cause parts of a window to be painted improperly.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162911%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162911%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />