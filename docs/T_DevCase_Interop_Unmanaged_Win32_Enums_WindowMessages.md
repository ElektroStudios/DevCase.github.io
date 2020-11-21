# WindowMessages Enumeration
 

The system sends or posts a system-defined message when it communicates with an application. 

 It uses these messages to control the operations of applications and to provide input and other information for applications to process. 

 An application can also send or post system-defined messages. 

 Applications generally use these messages to control the operation of control windows created by using preregistered window classes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum WindowMessages
```

**VB**<br />
``` VB
Public Enumeration WindowMessages
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowMessages
```

**C++**<br />
``` C++
public enum class WindowMessages
```

**F#**<br />
``` F#
type WindowMessages
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.Null">**Null**</td><td>0</td><td>The Null message performs no operation. 

 An application sends the Null message if it wants to send a message that the recipient window will ignore.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.MM_MciNotify">**MM_MciNotify**</td><td>953</td><td>Notifies an application that an MCI device has completed an operation. MCI devices send this message only when the `MCI_NOTIFY` flag is used. 

`wParam` Reason for the notification. 

`lParam` Identifier of the device initiating the callback function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.HWND_Broadcast">**HWND_Broadcast**</td><td>65535</td><td>The message is sent to all top-level windows in the system, including disabled or invisible unowned windows. 

 The function does not return until each window has timed out. Therefore, the total wait time can be up to the value of uTimeout multiplied by the number of top-level windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_AppCommand">**WM_AppCommand**</td><td>793</td><td>Notifies a window that the user generated an application command event, for example, by clicking an application command button using the mouse or typing an application command key on the keyboard. 

`wParam` A handle to the window where the user clicked the button or pressed the key. This can be a child window of the window receiving the message. 

`lParam` See Remarks.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SysCommand">**WM_SysCommand**</td><td>274</td><td>A window receives this message when the user chooses a command from the Window menu (formerly known as the system or control menu) or when the user chooses the maximize button, minimize button, restore button, or close button. 

`wParam` The type of system command requested 

`lParam` The low-order word specifies the horizontal position of the cursor, in screen coordinates, if a window menu command is chosen with the mouse. 

 Otherwise, this parameter is not used. 

 The high-order word specifies the vertical position of the cursor, in screen coordinates, if a window menu command is chosen with the mouse. 

 This parameter is –1 if the command is chosen using a system accelerator, or zero if using a mnemonic.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SettingChange">**WM_SettingChange**</td><td>26</td><td>A message that is sent to all top-level windows when the SystemParametersInfo function changes a system-wide setting or when policy settings have changed. 

 Applications should send WM_SettingChange to all top-level windows when they make changes to system parameters 

 This message cannot be sent directly to a single window. 

 To send the WM_SettingChange message to all top-level windows, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendMessageTimeout">SendMessageTimeout(IntPtr, EditControlMessages, IntPtr, IntPtr, SendMessageTimeoutFlags, Int32, IntPtr)</a> function with the `hwnd` parameter set to HWND_Broadcast. 

`wParam` See Remakrs. 

`lParam` See Remakrs.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Command">**WM_Command**</td><td>273</td><td>Message sent when the user selects a command item from a menu, when a control sends a notification message to its parent window, or when an accelerator keystroke is translated. 

`wParam` For a description of this parameter, see Remarks. 

`lParam` For a description of this parameter, see Remarks.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_GetText">**WM_GetText**</td><td>13</td><td>Copies the text that corresponds to a window into a buffer provided by the caller. 

`wParam` The maximum number of characters to be copied, including the terminating null character. 

 ANSI applications may have the string in the buffer reduced in size (to a minimum of half that of the wParam value) due to conversion from ANSI to Unicode. 

`lParam` A pointer to the buffer that is to receive the text.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_GetTextLength">**WM_GetTextLength**</td><td>14</td><td>Determines the length, in characters, of the text associated with a window. 

`wParam` This parameter is not used and must be zero 

`lParam` This parameter is not used and must be zero</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SetText">**WM_SetText**</td><td>12</td><td>Sets the text of a window. 

`wParam` This parameter is not used 

`lParam` A pointer to a null-terminated string that is the window text.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Close">**WM_Close**</td><td>16</td><td>Sent as a signal that a window or an application should terminate. 

`wParam` This parameter is not used. 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Move">**WM_Move**</td><td>3</td><td>Sent after a window has been moved. 

`wParam` This parameter is not used. 

`lParam` The x and y coordinates of the upper-left corner of the client area of the window. 

 The low-order word contains the x-coordinate while the high-order word contains the y coordinate.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcLButtonDown">**WM_NcLButtonDown**</td><td>161</td><td>Posted when the user presses the left mouse button while the cursor is within the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse, this message is not posted. 

`wParam` The hit-test value returned by the `DefWindowProc` function as a result of processing the WM_NchitTest message. 

`lParam` A `POINTS` structure that contains the x- and y-coordinates of the cursor. 

 The coordinates are relative to the upper-left corner of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcLButtonUp">**WM_NcLButtonUp**</td><td>162</td><td>Posted when the user releases the left mouse button while the cursor is within the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse, this message is not posted. 

`wParam` The hit-test value returned by the `DefWindowProc` function as a result of processing the WM_NchitTest message. 

`lParam` A `POINTS` structure that contains the x- and y-coordinates of the cursor. 

 The coordinates are relative to the upper-left corner of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcRButtonDown">**WM_NcRButtonDown**</td><td>164</td><td>Posted when the user presses the right mouse button while the cursor is within the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse, this message is not posted. 

`wParam` The hit-test value returned by the `DefWindowProc` function as a result of processing the WM_NchitTest message. 

`lParam` A `POINTS` structure that contains the x- and y-coordinates of the cursor. 

 The coordinates are relative to the upper-left corner of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcRButtonUp">**WM_NcRButtonUp**</td><td>165</td><td>Posted when the user releases the right mouse button while the cursor is within the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse, this message is not posted. 

`wParam` The hit-test value returned by the `DefWindowProc` function as a result of processing the WM_NchitTest message. 

`lParam` A `POINTS` structure that contains the x- and y-coordinates of the cursor. 

 The coordinates are relative to the upper-left corner of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_InitMenu">**WM_InitMenu**</td><td>278</td><td>Sent when a menu is about to become active. 

 It occurs when the user clicks an item on the menu bar or presses a menu key. 

 This allows the application to modify the menu before it is displayed. 

`wParam` A handle to the menu to be initialized. 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_InitMenuPopup">**WM_InitMenuPopup**</td><td>279</td><td>Sent when a drop-down menu or submenu is about to become active. 

 This allows an application to modify the menu before it is displayed, without changing the entire menu. 

`wParam` A handle to the drop-down menu or submenu. 

`lParam` The low-order word specifies the zero-based relative position of the menu item that opens the drop-down menu or submenu. 

 The high-order word indicates whether the drop-down menu is the window menu. 

 If the menu is the window menu, this parameter is `true` (`True` in Visual Basic); otherwise, it is `false` (`False` in Visual Basic).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NchitTest">**WM_NchitTest**</td><td>132</td><td>Sent to a window in order to determine what part of the window corresponds to a particular screen coordinate. 

 This can happen, for example, when the cursor moves, when a mouse button is pressed or released, or in response to a call to a function such as `WindowFromPoint`. 

 If the mouse is not captured, the message is sent to the window beneath the cursor. Otherwise, the message is sent to the window that has captured the mouse. 

`wParam` This parameter is not used. 

`lParam` The low-order word specifies the x-coordinate of the cursor. The coordinate is relative to the upper-left corner of the screen. 

 The high-order word specifies the y-coordinate of the cursor. The coordinate is relative to the upper-left corner of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Hotkey">**WM_Hotkey**</td><td>786</td><td>Posted when the user presses a hot key registered by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegisterHotKey">RegisterHotKey(IntPtr, Int32, UInt32, UInt32)</a> function. 

 The message is placed at the top of the message queue associated with the thread that registered the hot key. 

`wParam` The identifier of the hot key that generated the message. If the message was generated by a system-defined hot key. 

`lParam` The low-order word specifies the keys that were to be pressed in combination with the key specified by the high-order word to generate the WM_Hotkey message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SetRedraw">**WM_SetRedraw**</td><td>11</td><td>An application sends this message to a window to allow changes in that window to be redrawn or to prevent changes in that window from being redrawn. 

`wParam` The redraw state. 

 If this parameter is `true` (`True` in Visual Basic), the content can be redrawn after a change. 

 If this parameter is `false` (`False` in Visual Basic), the content cannot be redrawn after a change. 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Sizing">**WM_Sizing**</td><td>532</td><td>Sent to a window that the user is resizing. 

 By processing this message, an application can monitor the size and position of the drag rectangle and, if needed, change its size or position. 

`wParam` The edge of the window that is being sized. 

`lParam` A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure with the screen coordinates of the drag rectangle. 

 To change the size or position of the drag rectangle, an application must change the members of this structure.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_EnterSizeMove">**WM_EnterSizeMove**</td><td>561</td><td>Sent one time to a window, after it enters the moving or sizing modal loop. 

 The window enters the moving or sizing modal loop when the user clicks the window's title bar or sizing border, 

 or when the window passes the WM_SysCommand message to the `DefWindowProc` function and the `wParam` parameter of the message specifies the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">SC_Move</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">SC_Size</a> value. 

 The operation is complete when `DefWindowProc` returns. 

 The system sends the WM_EnterSizeMove message regardless of whether the dragging of full windows is enabled. 

`wParam` This parameter is not used. 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_ExitSizeMove">**WM_ExitSizeMove**</td><td>562</td><td>Sent one time to a window, after it has exited the moving or sizing modal loop. 

 The window enters the moving or sizing modal loop when the user clicks the window's title bar or sizing border, 

 or when the window passes the WM_SysCommand message to the `DefWindowProc` function and the `wParam` parameter of the message specifies the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">SC_Move</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">SC_Size</a> value. 

 The operation is complete when `DefWindowProc` returns. 

`wParam` This parameter is not used. 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_WindowPosChanging">**WM_WindowPosChanging**</td><td>70</td><td>Sent to a window whose size, position, or place in the Z order is about to change as a result of a call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowPos">SetWindowPos(IntPtr, IntPtr, Int32, Int32, Int32, Int32, SetWindowPosFlags)</a> function or another window-management function. 

`wParam` This parameter is not used. 

`lParam` A pointer to a `WINDOWPOS` structure that contains information about the window's new size and position.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcMouseMove">**WM_NcMouseMove**</td><td>160</td><td>This message is posted to a window when the cursor is moved within the nonclient area of the window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse this message is not posted. 

`wParam` The hit-test value returned by the `DefWindowProc` function as a result of processing the WM_NchitTest message. 

 For a list of hit-test values, see WM_NchitTest. 

`lParam` A `POINTS` structure that contains the x- and y-coordinates of the cursor. 

 The coordinates are relative to the upper-left corner of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MouseMove">**WM_MouseMove**</td><td>512</td><td>Posted to a window when the cursor moves. 

 If the mouse is not captured, the message is posted to the window that contains the cursor. 

 Otherwise, the message is posted to the window that has captured the mouse. 

`wParam` Indicates whether various virtual keys are down. 

`lParam` The low-order word specifies the x-coordinate of the cursor. The coordinate is relative to the upper-left corner of the client area. 

 The high-order word specifies the y-coordinate of the cursor. The coordinate is relative to the upper-left corner of the client area.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_ShowWindow">**WM_ShowWindow**</td><td>24</td><td>Sent to a window when the window is about to be hidden or shown. 

`wParam` Indicates whether a window is being shown. 

 If wParam is `true` (`True` in Visual Basic), the window is being shown. If wParam is `false` (`False` in Visual Basic), the window is being hidden. 

`lParam` The status of the window being shown. 

 If `lParam` is zero, the message was sent because of a call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShowWindow">ShowWindow(IntPtr, NativeWindowState)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Size">**WM_Size**</td><td>5</td><td>Sent to a window after its size has changed. 

`wParam` The type of resizing requested. 

`lParam` The low-order word of `lParam` specifies the new width of the client area. 

 The high-order word of `lParam` specifies the new height of the client area.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Activate">**WM_Activate**</td><td>6</td><td>The message is sent when a window is being activated or deactivated. 

 This message is sent first to the window procedure of the top-level window being deactivated; it is then sent to the window procedure of the top-level window being activated. 

`wParam` The low-order word specifies whether the window is being activated or deactivated. 

 This parameter can be one of the following values: 

 • <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">WA_Active</a> • <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">WA_ClickActive</a> • <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">WA_Inactive</a>

 The high-order word specifies the minimized state of the window being activated or deactivated. A nonzero value indicates the window is minimized. 

`lParam` A handle to the window being activated or deactivated, depending on the value of the wParam parameter. 

 If the low-order word of wParam is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">WA_Inactive</a>, lParam is the handle to the window being activated. 

 If the low-order word of wParam is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">WA_Active</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WParams">WA_ClickActive</a>, lParam is the handle to the window being deactivated. This handle can be Zero. 

`Return value` If an application processes this message, it should return zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_ActivateApp">**WM_ActivateApp**</td><td>28</td><td>The message is sent when a window belonging to a different application than the active window is about to be activated. 

 The message is sent to the application whose window is being activated and to the application whose window is being deactivated.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_ChangeUiState">**WM_ChangeUiState**</td><td>295</td><td>An application sends the message to indicate that the user interface (UI) state should be changed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Contextmenu">**WM_Contextmenu**</td><td>123</td><td>The message notifies a window that the user clicked the right mouse button (right-clicked) in the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Create">**WM_Create**</td><td>1</td><td>The message is sent when an application requests that a window be created by calling the `CreateWindowEx` or `CreateWindow` function. 

 (The message is sent before the function returns.) 

 The window procedure of the new window receives this message after the window is created but before the window becomes visible.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Destroy">**WM_Destroy**</td><td>2</td><td>The message is sent when a window is being destroyed. 

 It is sent to the window procedure of the window being destroyed after the window is removed from the screen. 

 This message is sent first to the window being destroyed and then to the child windows (if any) as they are destroyed. 

 During the processing of the message it can be assumed that all child windows still exist.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_DestroyClipboard">**WM_DestroyClipboard**</td><td>775</td><td>The message is sent to the clipboard owner when a call to the `EmptyClipboard` function empties the clipboard.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_DeviceChange">**WM_DeviceChange**</td><td>537</td><td>Notifies an application of a change to the hardware configuration of a device or the computer.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_DevmodeChange">**WM_DevmodeChange**</td><td>27</td><td>The message is sent to all top-level windows whenever the user changes device-mode settings.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_DisplayChange">**WM_DisplayChange**</td><td>126</td><td>The message is sent to all windows when the display resolution has changed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Enable">**WM_Enable**</td><td>10</td><td>The message is sent when an application changes the enabled state of a window. It is sent to the window whose enabled state is changing. 

 This message is sent before the EnableWindow function returns but after the enabled state (`WS_DISABLED` style bit) of the window has changed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_EndSession">**WM_EndSession**</td><td>22</td><td>The message is sent to an application after the system processes the results of the `WM_QUERYENDSESSION` message. 

 This message informs the application whether the session is ending.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_EnterIdle">**WM_EnterIdle**</td><td>289</td><td>The message is sent to the owner window of a modal dialog box or menu that is entering an idle state. 

 A modal dialog box or menu enters an idle state when no messages are waiting in its queue after it has processed one or more previous messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_EraseBkgnd">**WM_EraseBkgnd**</td><td>20</td><td>The message is sent when the window background must be erased (for example when a window is resized). 

 The message is sent to prepare an invalidated portion of a window for painting.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_FontChange">**WM_FontChange**</td><td>29</td><td>An application sends the message to all top-level windows in the system after changing the pool of font resources.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_GetHotkey">**WM_GetHotkey**</td><td>51</td><td>An application sends this message to determine the hot key associated with a window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_GetMinMaxInfo">**WM_GetMinMaxInfo**</td><td>36</td><td>The message is sent to a window when the size or position of the window is about to change. 

 An application can use this message to override the window's default maximized size and position or its default minimum or maximum tracking size.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Help">**WM_Help**</td><td>83</td><td>Indicates that the user pressed the `F1` key. 

 If a menu is active when `F1` is pressed WM_Help is sent to the window associated with the menu; otherwise WmHELP is sent to the window that has the keyboard focus. 

 If no window has the keyboard focus WM_Help is sent to the currently active window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_HScroll">**WM_HScroll**</td><td>276</td><td>This message is sent to a window when a scroll event occurs in the window's standard horizontal scroll bar. 

 This message is also sent to the owner of a horizontal scroll bar control when a scroll event occurs in the control.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_InitDialog">**WM_InitDialog**</td><td>272</td><td>The message is sent to the dialog box procedure immediately before a dialog box is displayed. 

 Dialog box procedures typically use this message to initialize controls and carry out any other initialization tasks that affect the appearance of the dialog box.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_KeyDown">**WM_KeyDown**</td><td>256</td><td>The message is posted to the window with the keyboard focus when a nonsystem key is pressed. 

 A nonsystem key is a key that is pressed when the `ALT` key is not pressed. 

`wParam` The virtual-key code of the nonsystem key. 

`lParam` The repeat count, scan code, extended-key flag, context code, previous key-state flag, and transition-state flag, as shown following: 

 Bit 0-15: The repeat count for the current message. 

 The value is the number of times the keystroke is autorepeated as a result of the user holding down the key. 

 If the keystroke is held long enough, multiple messages are sent. However, the repeat count is not cumulative 

 Bit 16-23: The scan code. The value depends on the OEM. 

 Bit 24: Indicates whether the key is an extended key, such as the right-hand ALT and CTRL keys that appear on an enhanced 101- or 102-key keyboard. 

 The value is 1 if it is an extended key; otherwise, it is 0. 

 Bit 25-28: Reserved; do not use 

 Bit 29: The context code. 

 The value is always 0 for a WM_KeyDown message. 

 Bit 30: The previous key state. 

 The value is 1 if the key is down before the message is sent, or it is zero if the key is up. 

 Bit 31: The transition state. 

 The value is always 0 for a WM_KeyDown message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_KeyUp">**WM_KeyUp**</td><td>257</td><td>The message is posted to the window with the keyboard focus when a nonsystem key is released. 

 A nonsystem key is a key that is pressed when the `ALT` key is not pressed or a keyboard key that is pressed when a window has the keyboard focus. 

`wParam` The virtual-key code of the nonsystem key. 

`lParam` The repeat count, scan code, extended-key flag, context code, previous key-state flag, and transition-state flag, as shown following: 

 Bit 0-15: The repeat count for the current message. 

 The value is the number of times the keystroke is autorepeated as a result of the user holding down the key. 

 The repeat count is always 1 for a WM_KeyUp message. 

 If the keystroke is held long enough, multiple messages are sent. However, the repeat count is not cumulative 

 Bit 16-23: The scan code. The value depends on the OEM. 

 Bit 24: Indicates whether the key is an extended key, such as the right-hand ALT and CTRL keys that appear on an enhanced 101- or 102-key keyboard. 

 The value is 1 if it is an extended key; otherwise, it is 0. 

 The value is 1 if it is an extended key; otherwise, it is 0. 

 Bit 25-28: Reserved; do not use 

 Bit 29: The context code. 

 The value is always 0 for a WM_KeyUp message. 

 Bit 30: The previous key state. 

 The value is always 1 for a WM_KeyUp message. 

 Bit 31: The transition state. 

 The value is always 1 for a WM_KeyUp message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_KillFocus">**WM_KillFocus**</td><td>8</td><td>The message is sent to a window immediately before it loses the keyboard focus.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_LButtonDblClk">**WM_LButtonDblClk**</td><td>515</td><td>The message is posted when the user double-clicks the left mouse button while the cursor is in the client area of a window. 

 If the mouse is not captured the message is posted to the window beneath the cursor. 

 Otherwise the message is posted to the window that has captured the mouse.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_LButtonDown">**WM_LButtonDown**</td><td>513</td><td>The message is posted when the user presses the left mouse button while the cursor is in the client area of a window. 

 If the mouse is not captured the message is posted to the window beneath the cursor. 

 Otherwise the message is posted to the window that has captured the mouse.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_LButtonUp">**WM_LButtonUp**</td><td>514</td><td>The message is posted when the user releases the left mouse button while the cursor is in the client area of a window. 

 If the mouse is not captured the message is posted to the window beneath the cursor. 

 Otherwise the message is posted to the window that has captured the mouse.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MButtonDblClk">**WM_MButtonDblClk**</td><td>521</td><td>The WmMBUTTONDBLCLK message is posted when the user double-clicks the middle mouse button while the cursor is in the client area of a window. 

 If the mouse is not captured the message is posted to the window beneath the cursor. 

 Otherwise the message is posted to the window that has captured the mouse.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MButtonDown">**WM_MButtonDown**</td><td>519</td><td>The message is posted when the user presses the middle mouse button while the cursor is in the client area of a window. 

 If the mouse is not captured the message is posted to the window beneath the cursor. 

 Otherwise the message is posted to the window that has captured the mouse.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MButtonUp">**WM_MButtonUp**</td><td>520</td><td>The message is posted when the user releases the middle mouse button while the cursor is in the client area of a window. 

 If the mouse is not captured the message is posted to the window beneath the cursor. 

 Otherwise the message is posted to the window that has captured the mouse.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MdiActivate">**WM_MdiActivate**</td><td>546</td><td>An application sends this message to a multiple-document interface (MDI) client window to instruct the client window to activate a different MDI child window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MdiCreate">**WM_MdiCreate**</td><td>544</td><td>An application sends this message to a multiple-document interface (MDI) client window to create an MDI child window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MdiDestroy">**WM_MdiDestroy**</td><td>545</td><td>An application sends this message to a multiple-document interface (MDI) client window to close an MDI child window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MenuCommand">**WM_MenuCommand**</td><td>294</td><td>The message is sent when the user makes a selection from a menu.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MenuRButtonUp">**WM_MenuRButtonUp**</td><td>290</td><td>The message is sent when the user releases the right mouse button while the cursor is on a menu item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MenuSelect">**WM_MenuSelect**</td><td>287</td><td>The message is sent to a menu's owner window when the user selects a menu item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MouseActivate">**WM_MouseActivate**</td><td>33</td><td>The message is sent when the cursor is in an inactive window and the user presses a mouse button. 

 The parent window receives this message only if the child window passes it to the `DefWindowProc` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MouseHover">**WM_MouseHover**</td><td>673</td><td>The message is posted to a window when the cursor hovers over the client area of the window for the period of time specified in a prior call to `TrackMouseEvent`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MouseLeave">**WM_MouseLeave**</td><td>675</td><td>The message is posted to a window when the cursor leaves the client area of the window specified in a prior call to `TrackMouseEvent`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MouseWheel">**WM_MouseWheel**</td><td>522</td><td>The message is sent to the focus window when the mouse wheel is rotated. 

 The `DefWindowProc` function propagates the message to the window's parent. 

 There should be no internal forwarding of the message since `DefWindowProc` propagates it up the parent chain until it finds a window that processes it. 

`wParam` The high-order word indicates the distance the wheel is rotated, expressed in multiples or divisions of WHEEL_DELTA, which is 120. A positive value indicates that the wheel was rotated forward, away from the user; a negative value indicates that the wheel was rotated backward, toward the user. 

 The low-order word indicates whether various virtual keys are down. 

`lParam` The low-order word specifies the x-coordinate of the pointer, relative to the upper-left corner of the screen. 

 The high-order word specifies the y-coordinate of the pointer, relative to the upper-left corner of the screen</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MouseHWheel">**WM_MouseHWheel**</td><td>526</td><td>The message is sent to the focus window when the mouse's horizontal scroll wheel is tilted or rotated. 

 The `DefWindowProc` function propagates the message to the window's parent. 

 There should be no internal forwarding of the message since `DefWindowProc` propagates it up the parent chain until it finds a window that processes it. 

`wParam` The high-order word indicates the distance the wheel is rotated, expressed in multiples or factors of WHEEL_DELTA, which is set to 120. A positive value indicates that the wheel was rotated to the right; a negative value indicates that the wheel was rotated to the left. 

 The low-order word indicates whether various virtual keys are down. 

`lParam` The low-order word specifies the x-coordinate of the pointer, relative to the upper-left corner of the screen. 

 The high-order word specifies the y-coordinate of the pointer, relative to the upper-left corner of the screen</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Moving">**WM_Moving**</td><td>534</td><td>The message is sent to a window that the user is moving. 

 By processing this message an application can monitor the position of the drag rectangle and if needed change its position.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcActivate">**WM_NcActivate**</td><td>134</td><td>Non Client Area Activated Caption(Title) of the Form.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcCalcSize">**WM_NcCalcSize**</td><td>131</td><td>The message is sent when the size and position of a window's client area must be calculated. 

 By processing this message an application can control the content of the window's client area when the size or position of the window changes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcCreate">**WM_NcCreate**</td><td>129</td><td>The message is sent prior to the WM_Create message when a window is first created.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcDestroy">**WM_NcDestroy**</td><td>130</td><td>The message informs a window that its nonclient area is being destroyed. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyWindow">DestroyWindow(IntPtr)</a> function sends the WM_NcDestroy message to the window following the WM_Destroy message. 

WM_Destroy is used to free the allocated memory object associated with the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcLButtonDblClk">**WM_NcLButtonDblClk**</td><td>163</td><td>The message is posted when the user double-clicks the left mouse button while the cursor is within the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse this message is not posted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcMButtonDblClk">**WM_NcMButtonDblClk**</td><td>169</td><td>The message is posted when the user double-clicks the middle mouse button while the cursor is within the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse this message is not posted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcMButtonDown">**WM_NcMButtonDown**</td><td>167</td><td>The message is posted when the user presses the middle mouse button while the cursor is within the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse this message is not posted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcMButtonUp">**WM_NcMButtonUp**</td><td>168</td><td>The message is posted when the user releases the middle mouse button while the cursor is within the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse this message is not posted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcMouseLeave">**WM_NcMouseLeave**</td><td>674</td><td>The message is posted to a window when the cursor leaves the nonclient area of the window specified in a prior call to `TrackMouseEvent`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcPaint">**WM_NcPaint**</td><td>133</td><td>The message is sent to a window when its frame must be painted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcRButtonDblClk">**WM_NcRButtonDblClk**</td><td>166</td><td>The message is posted when the user double-clicks the right mouse button while the cursor is within the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse this message is not posted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Paint">**WM_Paint**</td><td>15</td><td>Occurs when the control needs repainting.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_PowerBroadcast">**WM_PowerBroadcast**</td><td>536</td><td>Notifies applications that a power-management event has occurred.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Print">**WM_Print**</td><td>791</td><td>The message is sent to a window to request that it draw itself in the specified device context most commonly in a printer device context.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_PrintClient">**WM_PrintClient**</td><td>792</td><td>The message is sent to a window to request that it draw its client area in the specified device context most commonly in a printer device context.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_QueryEndSession">**WM_QueryEndSession**</td><td>17</td><td>The message is sent when the user chooses to end the session or when an application calls one of the system shutdown functions. 

 If any application returns zero the session is not ended. 

 The system stops sending WM_QueryEndSession messages as soon as one application returns zero. 

 After processing this message the system sends the WM_EndSession message with the `wParam` parameter set to the results of the WM_QueryEndSession message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Quit">**WM_Quit**</td><td>18</td><td>Once received it ends the application's Message Loop signaling the application to end. 

 It can be sent by pressing `Alt`+`F4` Clicking the X in the upper right-hand of the program or going to File->Exit.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_RButtonDblClk">**WM_RButtonDblClk**</td><td>518</td><td>The message is posted when the user double-clicks the right mouse button while the cursor is in the client area of a window. 

 If the mouse is not captured the message is posted to the window beneath the cursor. 

 Otherwise the message is posted to the window that has captured the mouse.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_RButtonDown">**WM_RButtonDown**</td><td>516</td><td>The message is posted when the user presses the right mouse button while the cursor is in the client area of a window. 

 If the mouse is not captured the message is posted to the window beneath the cursor. 

 Otherwise the message is posted to the window that has captured the mouse.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_RButtonUp">**WM_RButtonUp**</td><td>517</td><td>The message is posted when the user releases the right mouse button while the cursor is in the client area of a window. 

 If the mouse is not captured the message is posted to the window beneath the cursor. 

 Otherwise the message is posted to the window that has captured the mouse.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SetFocus">**WM_SetFocus**</td><td>7</td><td>When the control got the focus.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SetHotkey">**WM_SetHotkey**</td><td>50</td><td>An application sends this message to a window to associate a hot key with the window. 

 When the user presses the hot key the system activates the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SpoolerStatus">**WM_SpoolerStatus**</td><td>42</td><td>The message is sent from Print Manager whenever a job is added to or removed from the Print Manager queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_StyleChanged">**WM_StyleChanged**</td><td>125</td><td>The message is sent to a window after the `SetWindowLong` function has changed one or more of the window's styles.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_StyleChanging">**WM_StyleChanging**</td><td>124</td><td>The message is sent to a window when the `SetWindowLong` function is about to change one or more of the window's styles.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SysColorChange">**WM_SysColorChange**</td><td>21</td><td>This message is sent to all top-level windows when a change is made to a system color setting.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SysKeyDown">**WM_SysKeyDown**</td><td>260</td><td>The message is posted to the window with the keyboard focus when the user presses the `F10` key (which activates the menu bar) or holds down the `ALT` key and then presses another key. 

 It also occurs when no window currently has the keyboard focus; in this case the WM_SysKeyDown message is sent to the active window. 

 The window that receives the message can distinguish between these two contexts by checking the context code in the `lParam` parameter. 

`wParam` The virtual-key code of the key being pressed. 

`lParam` The repeat count, scan code, extended-key flag, context code, previous key-state flag, and transition-state flag, as shown following: 

 Bit 0-15: The repeat count for the current message. The value is the number of times the keystroke is autorepeated as a result of the user holding down the key. 

 If the keystroke is held long enough, multiple messages are sent. However, the repeat count is not cumulative. 

 Bit 16-23: The scan code. The value depends on the OEM. 

 Bit 24: Indicates whether the key is an extended key, such as the right-hand ALT and CTRL keys that appear on an enhanced 101- or 102-key keyboard. 

 The value is 1 if it is an extended key; otherwise, it is 0. 

 Bit 25-28: Reserved; do not use 

 Bit 29: The context code. 

 The value is 1 if the ALT key is down while the key is pressed; it is 0 if the WM_SysKeyDown message is posted to the active window because no window has the keyboard focus. 

 Bit 30: The previous key state. 

 The value is 1 if the key is down before the message is sent, or it is 0 if the key is up. 

 Bit 31: The transition state. 

 The value is always 0 for a WM_SysKeyDown message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SysKeyUp">**WM_SysKeyUp**</td><td>261</td><td>The message is posted to the window with the keyboard focus when the user releases a key that was pressed while the `ALT` key was held down. 

 It also occurs when no window currently has the keyboard focus; in this case the WM_SysKeyUp message is sent to the active window. 

 The window that receives the message can distinguish between these two contexts by checking the context code in the `lParam` parameter. 

`wParam` The virtual-key code of the key being released. 

`lParam` The repeat count, scan code, extended-key flag, context code, previous key-state flag, and transition-state flag, as shown following: 

 Bit 0-15: The repeat count for the current message. 

 The value is the number of times the keystroke is autorepeated as a result of the user holding down the key. 

 The repeat count is always one for a WM_SysKeyUp message. 

 Bit 16-23: The scan code. The value depends on the OEM. 

 Bit 24: Indicates whether the key is an extended key, such as the right-hand ALT and CTRL keys that appear on an enhanced 101- or 102-key keyboard. 

 The value is 1 if it is an extended key; otherwise, it is zero. 

 Bit 25-28: Reserved; do not use 

 Bit 29: The context code. 

 The value is 1 if the ALT key is down while the key is released; it is zero if the WM_SysKeyDown message is posted to the active window because no window has the keyboard focus. 

 Bit 30: The previous key state. 

 The value is always 1 for a WM_SysKeyUp message. 

 Bit 31: The transition state. 

 The value is always 1 for a WM_SysKeyUp message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_TimeChange">**WM_TimeChange**</td><td>30</td><td>A message that is sent whenever there is a change in the system time.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Undo">**WM_Undo**</td><td>772</td><td>An application sends this message to an edit control to undo the last operation. 

 When this message is sent to an edit control the previously deleted text is restored or the previously added text is deleted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_UserChanged">**WM_UserChanged**</td><td>84</td><td>The message is sent to all windows after the user has logged on or off. 

 When the user logs on or off the system updates the user-specific settings. 

 The system sends this message immediately after updating the settings.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_VScroll">**WM_VScroll**</td><td>277</td><td>The message is sent to a window when a scroll event occurs in the window's standard vertical scroll bar. 

 This message is also sent to the owner of a vertical scroll bar control when a scroll event occurs in the control.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_WindowPosChanged">**WM_WindowPosChanged**</td><td>71</td><td>The message is sent to a window whose size position or place in the Z order has changed as a result of a call to the `SetWindowPos` function or another window-management function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Copy">**WM_Copy**</td><td>769</td><td>An application sends this message to an edit control or combo box to copy the current selection to the clipboard in `CF_TEXT` format. 

`wParam` This parameter is not used and must be zero. 

`lParam` This parameter is not used and must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Cut">**WM_Cut**</td><td>768</td><td>An application sends this message to an edit control or combo box to delete (cut) the current selection if any in the edit control and copy the deleted text to the clipboard in `CF_TEXT` format. 

`wParam` This parameter is not used and must be zero. 

`lParam` This parameter is not used and must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Paste">**WM_Paste**</td><td>770</td><td>An application sends this message to an edit control or combo box to copy the current content of the clipboard to the edit control at the current caret position. 

 Data is inserted only if the clipboard contains data in `CF_TEXT` format. 

`wParam` This parameter is not used and must be zero. 

`lParam` This parameter is not used and must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Clear">**WM_Clear**</td><td>771</td><td>An application sends the message to an edit control or combo box to delete (clear) the current selection if any from the edit control. 

`wParam` This parameter is not used and must be zero. 

`lParam` This parameter is not used and must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_XButtonDown">**WM_XButtonDown**</td><td>523</td><td>Posted when the user presses the first or second X button while the cursor is in the client area of a window. 

 If the mouse is not captured, the message is posted to the window beneath the cursor. 

 Otherwise, the message is posted to the window that has captured the mouse. 

`wParam` The low-order word indicates whether various virtual keys are down. 

 The high-order word indicates which button was clicked. 

`lParam` The low-order word specifies the x-coordinate of the cursor. The coordinate is relative to the upper-left corner of the client area. 

 The high-order word specifies the y-coordinate of the cursor. The coordinate is relative to the upper-left corner of the client area.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_XButtonUp">**WM_XButtonUp**</td><td>524</td><td>Posted when the user releases the first or second X button while the cursor is in the client area of a window. 

 If the mouse is not captured, the message is posted to the window beneath the cursor. 

 Otherwise, the message is posted to the window that has captured the mouse. 

`wParam` The low-order word indicates whether various virtual keys are down. 

 The high-order word indicates which button was double-clicked. 

`lParam` The low-order word specifies the x-coordinate of the cursor. The coordinate is relative to the upper-left corner of the client area. 

 The high-order word specifies the y-coordinate of the cursor. The coordinate is relative to the upper-left corner of the client area.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_XButtonDblClk">**WM_XButtonDblClk**</td><td>525</td><td>Posted when the user double-clicks the first or second X button while the cursor is in the client area of a window. 

 If the mouse is not captured, the message is posted to the window beneath the cursor. 

 Otherwise, the message is posted to the window that has captured the mouse. 

`wParam` The low-order word indicates whether various virtual keys are down. 

 The high-order word indicates which button was double-clicked. 

`lParam` The low-order word specifies the x-coordinate of the cursor. The coordinate is relative to the upper-left corner of the client area. 

 The high-order word specifies the y-coordinate of the cursor. The coordinate is relative to the upper-left corner of the client area.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcXButtonDown">**WM_NcXButtonDown**</td><td>171</td><td>Posted when the user presses the first or second X button while the cursor is in the client area of a window. 

 If the mouse is not captured, the message is posted to the window beneath the cursor. 

 Otherwise, the message is posted to the window that has captured the mouse. 

`wParam` The low-order word specifies the hit-test value returned by the `DefWindowProc` function from processing the WM_NchitTest message. 

 For a list of hit-test values, WM_NchitTest. 

 The high-order word indicates which button was pressed. 

`lParam` A pointer to a `POINTS` structure that contains the x- and y-coordinates of the cursor. 

 The coordinates are relative to the upper-left corner of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcXButtonUp">**WM_NcXButtonUp**</td><td>172</td><td>Posted when the user releases the first or second X button while the cursor is in the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse, this message is not posted. 

`wParam` The low-order word specifies the hit-test value returned by the `DefWindowProc` function from processing the WM_NchitTest message. 

 For a list of hit-test values, WM_NchitTest. 

 The high-order word indicates which button was released. 

`lParam` A pointer to a `POINTS` structure that contains the x- and y-coordinates of the cursor. 

 The coordinates are relative to the upper-left corner of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_NcXButtonDblClk">**WM_NcXButtonDblClk**</td><td>173</td><td>Posted when the user double-clicks the first or second X button while the cursor is in the nonclient area of a window. 

 This message is posted to the window that contains the cursor. 

 If a window has captured the mouse, this message is not posted. 

`wParam` The low-order word specifies the hit-test value returned by the `DefWindowProc` function from processing the WM_NchitTest message. 

 For a list of hit-test values, WM_NchitTest. 

 The high-order word indicates which button was double-clicked. 

`lParam` A pointer to a `POINTS` structure that contains the x- and y-coordinates of the cursor. 

 The coordinates are relative to the upper-left corner of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Input">**WM_Input**</td><td>255</td><td>Sent to the window that is getting raw input. 

 A window receives this message through its `WndProc` function. 

`wParam` The input code. 

`lParam` A handle to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structure that contains the raw input from the device. 

 Call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceInfo">GetRawInputDeviceInfo(IntPtr, GetRawInputDeviceInfoCommand, IntPtr, UInt32)</a> to get more information regarding the device.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_InputDeviceChange">**WM_InputDeviceChange**</td><td>254</td><td>Sent to the window that registered to receive raw input. 

 A window receives this message through its `WndProc` function. 

`wParam` This parameter can be one of the following values. 

 GIDC_ARRIVAL (`1`): A new device has been added to the system. 

 GIDC_REMOVAL (`0`): A new device has been removed from the system. 

`lParam` A handle to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structure that contains the raw input from the device. 

 Call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceInfo">GetRawInputDeviceInfo(IntPtr, GetRawInputDeviceInfoCommand, IntPtr, UInt32)</a> to get more information regarding the device.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_DwmSendIconicThumbnail">**WM_DwmSendIconicThumbnail**</td><td>803</td><td>Instructs a window to provide a static bitmap to use as a thumbnail representation of that window. 

 Desktop Window Manager (DWM) sends this message to a window if all of the following situations are true: 

`DWM` is displaying an iconic representation of the window. 

 The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmWindowAttribute">HasIconicBitmap</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmWindowAttribute">ForceIconicRepresentation</a> attributes are set on the window. 

 The window did not set a cached bitmap. 

 There is room in the cache for another bitmap. 

`wParam` Not used. 

`lParam` The `HIWORD` of this value is the maximum possible width of the thumbnail. 

 The `LOWORD` is the maximum possible height. 

 If a thumbnail has a dimension that exceeds one or both of these values, the `DWM` does not accept the thumbnail.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_DwmSendIconicLivePreviewBitmap">**WM_DwmSendIconicLivePreviewBitmap**</td><td>806</td><td>Instructs a window to provide a static bitmap to use as a live preview (also known as a `Peek preview`) of that window. 

 Desktop Window Manager (DWM) sends this message to a window if all of the following situations are true: 

 Live preview has been invoked on the window 

 The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmWindowAttribute">HasIconicBitmap</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmWindowAttribute">ForceIconicRepresentation</a> attributes are set on the window. 

 An iconic representation is the only one that exists for this window. 

`wParam` Not used. 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_DwmCompositionChanged">**WM_DwmCompositionChanged**</td><td>798</td><td>Informs all top-level windows that Desktop Window Manager (DWM) composition has been enabled or disabled. 

 Note: As of Windows 8/8.1/10, DWM composition is always enabled, so this message is not sent regardless of video mode changes. 

`wParam` Not used. 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.Wm_DwmNcRenderingChanged">**Wm_DwmNcRenderingChanged**</td><td>799</td><td>Sent when the non-client area rendering policy has changed. 

`wParam` Specifies whether DWM rendering is enabled for the non-client area of the window. `true` (`True` in Visual Basic) if enabled; otherwise, `false` (`False` in Visual Basic). 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_DwmColorizationColorChanged">**WM_DwmColorizationColorChanged**</td><td>800</td><td>Informs all top-level windows that the colorization color has changed. 

`wParam` Specifies the new colorization color.

 The color format is `0xAARRGGBB`. 

`lParam` Specifies whether the new color is blended with opacity.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_DwmWindowMaximizedChanged">**WM_DwmWindowMaximizedChanged**</td><td>801</td><td>Sent when a Desktop Window Manager (DWM) composed window is maximized. 

`wParam` Set to true to specify that the window has been maximized. 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_CancelMode">**WM_CancelMode**</td><td>31</td><td>Sent to cancel certain modes, such as mouse capture. 

 For example, the system sends this message to the active window when a dialog box or message box is displayed. 

 Certain functions also send this message explicitly to the specified window regardless of whether it is the active window. 

 For example, the EnableWindow function sends this message when disabling the specified window. 

`wParam` Not used. 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_QueryOpen">**WM_QueryOpen**</td><td>19</td><td>Sent to an icon when the user requests that the window be restored to its previous size and position. 

`wParam` Not used. 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_SetFont">**WM_SetFont**</td><td>48</td><td>Sets the font that a control is to use when drawing text. 

`wParam` A handle to the font (HFONT). 

 If this parameter is a null reference (`Nothing` in Visual Basic), the control uses the default system font to draw text. 

`lParam` The low-order word of lParam specifies whether the control should be redrawn immediately upon setting the font. 

 If this parameter is TRUE, the control redraws itself.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_App">**WM_App**</td><td>32768</td><td>Used to define private messages, usually of the form 'WM_App + x', where 'x' is an integer value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_User">**WM_User**</td><td>1024</td><td>Used to define private messages for use by private window classes, usually of the form 'WM_User + x', where 'x' is an integer value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_CtlColorEdit">**WM_CtlColorEdit**</td><td>307</td><td>An edit control that is not read-only or disabled sends the WM_CtlColorEdit message to its parent window when the control is about to be drawn. 

 By responding to this message, the parent window can use the specified device context handle to set the text and background colors of the edit control. 

`wParam` A handle to the device context for the edit control window. 

`lParam` A handle to the edit control.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_KeyFirst">**WM_KeyFirst**</td><td>256</td><td>This message filters for keyboard messages. 

 Use the WM_KeyFirst and WM_KeyLast messages to filter for keyboard messages when using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> functions. 

`wParam` Not used. 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_KeyLast">**WM_KeyLast**</td><td>265</td><td>This message filters for keyboard messages. 

 Use the WM_KeyFirst and WM_KeyLast messages to filter for keyboard messages when using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> functions. 

`wParam` Not used. 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MouseFirst">**WM_MouseFirst**</td><td>512</td><td>This message filters for mouse messages. 

 Use the WM_MouseFirst and WM_MouseLast messages to filter for mouse messages when using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> functions. 

`wParam` Not used. 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_MouseLast">**WM_MouseLast**</td><td>522</td><td>This message filters for mouse messages. 

 Use the WM_MouseFirst and WM_MouseLast messages to filter for mouse messages when using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> functions. 

`wParam` Not used. 

`lParam` Not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages.WM_Timer">**WM_Timer**</td><td>275</td><td>Posted to the installing thread's message queue when a timer expires. 

 The message is posted by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> function. 

`wParam` The timer identifier. 

`lParam` A pointer to an application-defined callback function that was passed to the SetTimer function when the timer was installed.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644927%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644927%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />