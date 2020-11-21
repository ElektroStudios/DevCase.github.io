# SpecialWindowHandles Enumeration
 

A handle to the window to precede the positioned window in the Z order. 

`hwndInsertAfter` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowPos">SetWindowPos(IntPtr, IntPtr, Int32, Int32, Int32, Int32, SetWindowPosFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum SpecialWindowHandles
```

**VB**<br />
``` VB
Public Enumeration SpecialWindowHandles
```

**VB Usage**<br />
``` VB Usage
Dim instance As SpecialWindowHandles
```

**C++**<br />
``` C++
public enum class SpecialWindowHandles
```

**F#**<br />
``` F#
type SpecialWindowHandles
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SpecialWindowHandles.Top">**Top**</td><td>0</td><td>Places the window at the top of the Z order.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SpecialWindowHandles.Bottom">**Bottom**</td><td>1</td><td>Places the window at the bottom of the Z order. 

 If the hwnd parameter identifies a topmost window, the window loses its topmost status and is placed at the bottom of all other windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SpecialWindowHandles.TopMost">**TopMost**</td><td>-1</td><td>Places the window above all non-topmost windows. 

 The window maintains its topmost position even when it is deactivated.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SpecialWindowHandles.NoTopMost">**NoTopMost**</td><td>-2</td><td>Places the window above all non-topmost windows (that is, behind all topmost windows). 

 This flag has no effect if the window is already a non-topmost window.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />