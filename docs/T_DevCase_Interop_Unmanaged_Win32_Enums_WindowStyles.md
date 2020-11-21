# WindowStyles Enumeration
 

The following styles can be specified wherever a window style is required. 

 After the control has been created, these styles cannot be modified, except as noted.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum WindowStyles
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration WindowStyles
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowStyles
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class WindowStyles
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type WindowStyles
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.None">**None**</td><td>0</td><td>No style.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Border">**Border**</td><td>8388608</td><td>The window has a thin-line border.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Caption">**Caption**</td><td>12582912</td><td>The window has a title bar. 

 (includes the Border style).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Child">**Child**</td><td>1073741824</td><td>The window is a child window. 

 A window with this style cannot have a menu bar. 

 This style cannot be used with the Popup style.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.ClipChildren">**ClipChildren**</td><td>33554432</td><td>Excludes the area occupied by child windows when drawing occurs within the parent window. 

 This style is used when creating the parent window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.ClipSiblings">**ClipSiblings**</td><td>67108864</td><td>Clips child windows relative to each other; that is, when a particular child window receives a `WM_PAINT` message, the ClipSiblings style clips all other overlapping child windows out of the region of the child window to be updated. 

 If ClipSiblings is not specified and child windows overlap, it is possible, when drawing within the client area of a child window, to draw within the client area of a neighboring child window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Disabled">**Disabled**</td><td>134217728</td><td>The window is initially disabled. 

 A disabled window cannot receive input from the user. 

 To change this after a window has been created, use the `EnableWindow` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.DlgFrame">**DlgFrame**</td><td>4194304</td><td>The window has a border of a style typically used with dialog boxes. 

 A window with this style cannot have a title bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Group">**Group**</td><td>131072</td><td>The window is the first control of a group of controls. 

 The group consists of this first control and all controls defined after it, up to the next control with the Group style. 

 The first control in each group usually has the TabStop style so that the user can move from group to group. 

 The user can subsequently change the keyboard focus from one control in the group to the next control in the group by using the direction keys. 

 You can turn this style on and off to change dialog box navigation. 

 To change this style after a window has been created, use the `SetWindowLong` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.HScroll">**HScroll**</td><td>1048576</td><td>The window has a horizontal scroll bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Maximize">**Maximize**</td><td>16777216</td><td>The window is initially maximized.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.MaximizeBox">**MaximizeBox**</td><td>65536</td><td>The window has a maximize button. 

 Cannot be combined with the `WS_EX_CONTEXTHELP` extended style. 

 The SysMenu style must also be specified.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Minimize">**Minimize**</td><td>536870912</td><td>The window is initially minimized.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.MinimizeBox">**MinimizeBox**</td><td>131072</td><td>The window has a minimize button. 

 Cannot be combined with the `WS_EX_CONTEXTHELP` extended style. 

 The SysMenu style must also be specified.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Overlapped">**Overlapped**</td><td>0</td><td>The window is an overlapped window. 

 An overlapped window has a title bar and a border.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.OverlappedWindow">**OverlappedWindow**</td><td>13565952</td><td>The window is an overlapped window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Popup">**Popup**</td><td>2147483648</td><td>The window is a pop-up window. 

 This style cannot be used with the Child style.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.PopupWindow">**PopupWindow**</td><td>2156396544</td><td>The window is a pop-up window. 

 The Caption and PopupWindow styles must be combined to make the window menu visible.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.SizeFrame">**SizeFrame**</td><td>262144</td><td>The window has a sizing border.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.SysMenu">**SysMenu**</td><td>524288</td><td>The window has a window menu on its title bar. 

 The Caption style must also be specified.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.TabStop">**TabStop**</td><td>65536</td><td>The window is a control that can receive the keyboard focus when the user presses the `TAB` key. 

 Pressing the `TAB` key changes the keyboard focus to the next control with the TabStop style. 

 You can turn this style on and off to change dialog box navigation. 

 To change this style after a window has been created, use the `SetWindowLong` function. 

 For user-created windows and modeless dialogs to work with tab stops, alter the message loop to call the `IsDialogMessage` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.Visible">**Visible**</td><td>268435456</td><td>The window is initially visible. 

 This style can be turned on and off by using the `ShowWindow` or `SetWindowPos` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles.VScroll">**VScroll**</td><td>2097152</td><td>The window has a vertical scroll bar.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms632600%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms632600%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />