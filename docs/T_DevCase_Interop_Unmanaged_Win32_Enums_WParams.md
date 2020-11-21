# WParams Enumeration
 

Specifies additional message-specific information for various system-defined messages.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum WParams
```

**VB**<br />
``` VB
Public Enumeration WParams
```

**VB Usage**<br />
``` VB Usage
Dim instance As WParams
```

**C++**<br />
``` C++
public enum class WParams
```

**F#**<br />
``` F#
type WParams
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.Null">**Null**</td><td>0</td><td>A Null WParam.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.MinimizeAll">**MinimizeAll**</td><td>419</td><td>Minimize all windows. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Command</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.UndoMinimizeAll">**UndoMinimizeAll**</td><td>416</td><td>Undo the minimization of all minimized windows. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Command</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_MonitorPower">**SC_MonitorPower**</td><td>61808</td><td>Sets the state of the display. 

 This command supports devices that have power-saving features, such as a battery-powered personal computer 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_Move">**SC_Move**</td><td>61456</td><td>Moves the window. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_Size">**SC_Size**</td><td>61440</td><td>Sizes the window. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_DragMove">**SC_DragMove**</td><td>61458</td><td>Drags the window. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_Minimize">**SC_Minimize**</td><td>61472</td><td>Minimizes the window. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_Maximize">**SC_Maximize**</td><td>61488</td><td>Maximizes the window. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_Close">**SC_Close**</td><td>61536</td><td>Closes the window. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_HScroll">**SC_HScroll**</td><td>61568</td><td>Scrolls horizontally. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_VScroll">**SC_VScroll**</td><td>61552</td><td>Scrolls vertically. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_KeyMenu">**SC_KeyMenu**</td><td>61696</td><td>Retrieves the window menu as a result of a keystroke. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_MouseMenu">**SC_MouseMenu**</td><td>61584</td><td>Retrieves the window menu as a result of a mouse click. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysCommand</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.SC_Screensaver">**SC_Screensaver**</td><td>61760</td><td>Runs the default screensaver. 

 ( the screensaver should be enabled. ) 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Command</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.EC_LeftMargin">**EC_LeftMargin**</td><td>3</td><td>Sets the left margin for an edit control. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EditControlMessages">SetMargins</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.EC_RightMargin">**EC_RightMargin**</td><td>2</td><td>Sets the right margin for an edit control. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EditControlMessages">SetMargins</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.PBST_Normal">**PBST_Normal**</td><td>1</td><td>Sets the state of a progressbar to Normal (Green Color). 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProgressBarMessages">SetState</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.PBST_Error">**PBST_Error**</td><td>2</td><td>Sets the state of a progressbar to Error (Red Color). 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProgressBarMessages">SetState</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.PBST_Paused">**PBST_Paused**</td><td>3</td><td>Sets the state of a progressbar to Paused (Yellow Color). 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProgressBarMessages">SetState</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.WA_Active">**WA_Active**</td><td>1</td><td>Window is activated by some method other than a mouse click 

 (for example, by a call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetActiveWindow">SetActiveWindow(IntPtr)</a> function or by use of the keyboard interface to select the window). 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Activate</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.WA_ClickActive">**WA_ClickActive**</td><td>2</td><td>Window is activated by a mouse click. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Activate</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.WA_Inactive">**WA_Inactive**</td><td>0</td><td>Window is deactivated. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Activate</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.MK_Control">**MK_Control**</td><td>8</td><td>The CTRL key is down. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonDown</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonUp</a> messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.MK_LButton">**MK_LButton**</td><td>1</td><td>The left mouse button is down. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonDown</a> message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.MK_MButton">**MK_MButton**</td><td>16</td><td>The middle mouse button is down. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonDown</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonUp</a> messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.MK_RButton">**MK_RButton**</td><td>2</td><td>The right mouse button is down. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonDown</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonUp</a> messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.MK_Shift">**MK_Shift**</td><td>4</td><td>The SHIFT key is down. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonDown</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonUp</a> messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.MK_XButton1">**MK_XButton1**</td><td>32</td><td>The first X button is down. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonDown</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonUp</a> messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WParams.MK_XButton2">**MK_XButton2**</td><td>64</td><td>The second X button is down. 

 wParam to use with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonDown</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonUp</a> messages.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644927%28v=vs.85%29.aspx#system_defined" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644927%28v=vs.85%29.aspx#system_defined</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />