# ScrollBarOrientation Enumeration
 

Flags combination for `bar` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetScrollInfo">GetScrollInfo(IntPtr, ScrollBarOrientation, ScrollInfo)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetScrollInfo">SetScrollInfo(IntPtr, ScrollBarOrientation, ScrollInfo, Boolean)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShowScrollBar">ShowScrollBar(IntPtr, ScrollBarOrientation, Boolean)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ScrollBarOrientation
```

**VB**<br />
``` VB
Public Enumeration ScrollBarOrientation
```

**VB Usage**<br />
``` VB Usage
Dim instance As ScrollBarOrientation
```

**C++**<br />
``` C++
public enum class ScrollBarOrientation
```

**F#**<br />
``` F#
type ScrollBarOrientation
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollBarOrientation.Horizontal">**Horizontal**</td><td>0</td><td>Retrieves the parameters for the window's standard horizontal scrollbar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollBarOrientation.Vertical">**Vertical**</td><td>1</td><td>Retrieves the parameters for the window's standard vertical scrollbar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollBarOrientation.Control">**Control**</td><td>2</td><td>Retrieves the parameters for a scrollbar control. 

 The `hwnd` parameter must be the handle to the scrollbar control.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollBarOrientation.Both">**Both**</td><td>3</td><td>Retrieves the parameters for the window's standard horizontal and vertical scrollbars.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/bb787583%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/bb787583%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />