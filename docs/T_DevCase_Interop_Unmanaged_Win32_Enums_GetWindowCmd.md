# GetWindowCmd Enumeration
 

The relationship between the specified window and the window whose handle is to be retrieved. 

`gwCmd` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindow">GetWindow(IntPtr, GetWindowCmd)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum GetWindowCmd
```

**VB**<br />
``` VB
Public Enumeration GetWindowCmd
```

**VB Usage**<br />
``` VB Usage
Dim instance As GetWindowCmd
```

**C++**<br />
``` C++
public enum class GetWindowCmd
```

**F#**<br />
``` F#
type GetWindowCmd
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetWindowCmd.HwndFirst">**HwndFirst**</td><td>0</td><td>The retrieved handle identifies the window of the same type that is highest in the Z order. 

 If the specified window is a topmost window, the handle identifies a topmost window. 

 If the specified window is a top-level window, the handle identifies a top-level window. 

 If the specified window is a child window, the handle identifies a sibling window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetWindowCmd.HwndLast">**HwndLast**</td><td>1</td><td>The retrieved handle identifies the window of the same type that is lowest in the Z order. 

 If the specified window is a topmost window, the handle identifies a topmost window. 

 If the specified window is a top-level window, the handle identifies a top-level window. 

 If the specified window is a child window, the handle identifies a sibling window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetWindowCmd.HwndNext">**HwndNext**</td><td>2</td><td>The retrieved handle identifies the window below the specified window in the Z order. 

 If the specified window is a topmost window, the handle identifies a topmost window. 

 If the specified window is a top-level window, the handle identifies a top-level window. 

 If the specified window is a child window, the handle identifies a sibling window</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetWindowCmd.HwndPrev">**HwndPrev**</td><td>3</td><td>The retrieved handle identifies the window above the specified window in the Z order. 

 If the specified window is a topmost window, the handle identifies a topmost window. 

 If the specified window is a top-level window, the handle identifies a top-level window. 

 If the specified window is a child window, the handle identifies a sibling window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetWindowCmd.Owner">**Owner**</td><td>4</td><td>The retrieved handle identifies the specified window's owner window, if any. 

 For more information, see <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms632599(v=vs.85).aspx#owned_windows" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms632599(v=vs.85).aspx#owned_windows</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetWindowCmd.Child">**Child**</td><td>5</td><td>The retrieved handle identifies the child window at the top of the Z order, if the specified window is a parent window; 

 otherwise, the retrieved handle is Zero. 

 The function examines only child windows of the specified window. It does not examine descendant windows</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetWindowCmd.EnabledPopup">**EnabledPopup**</td><td>6</td><td>The retrieved handle identifies the enabled popup window owned by the specified window (the search uses the first such window found using GW_HWNDNEXT); 

 otherwise, if there are no enabled popup windows, the retrieved handle is that of the specified window.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633515%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633515%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />