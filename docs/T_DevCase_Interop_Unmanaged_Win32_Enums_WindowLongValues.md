# WindowLongValues Enumeration
 

Specifies the zero-based offset to the value to be get or set on a window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum WindowLongValues
```

**VB**<br />
``` VB
Public Enumeration WindowLongValues
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowLongValues
```

**C++**<br />
``` C++
public enum class WindowLongValues
```

**F#**<br />
``` F#
type WindowLongValues
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.UserData">**UserData**</td><td>-21</td><td>Retrieves the user data associated with the window. 

 This data is intended for use by the application that created the window. 

 Its value is initially zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.WindowStyleEx">**WindowStyleEx**</td><td>-20</td><td>Retrieves the extended window styles.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.WindowStyle">**WindowStyle**</td><td>-16</td><td>Retrieves the window styles.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.Id">**Id**</td><td>-12</td><td>Retrieves the identifier of the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.HwndParent">**HwndParent**</td><td>-8</td><td>Retrieves a handle to the parent window, if any.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.HInstance">**HInstance**</td><td>-6</td><td>Retrieves a handle to the application instance.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.WndProc">**WndProc**</td><td>-4</td><td>Retrieves the address of the window procedure, or a handle representing the address of the window procedure. 

 You must use the `CallWindowProc` function to call the window procedure.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.DlgMsgresult">**DlgMsgresult**</td><td>0</td><td>( This value is only available when the `hwnd` parameter identifies a dialog box. ) 

 Retrieves the return value of a message processed in the dialog box procedure.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.DlgProc">**DlgProc**</td><td>4</td><td>( This value is only available when the `hwnd` parameter identifies a dialog box. ) 

 Retrieves the address of the dialog box procedure, or a handle representing the address of the dialog box procedure. 

 You must use the `CallWindowProc` function to call the dialog box procedure.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues.DlgUser">**DlgUser**</td><td>8</td><td>( This value is only available when the `hwnd` parameter identifies a dialog box. ) 

 Retrieves extra information private to the application, such as handles or pointers.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowlongptra" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowlongptra</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />