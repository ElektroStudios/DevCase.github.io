# NativeMethods.SetScrollInfo Method (SafeHandle, ScrollBarOrientation, ScrollInfo, Boolean)
 

Sets the parameters of a scroll bar, including the minimum and maximum scrolling positions, the page size, and the position of the scroll box (thumb). 

 The function also redraws the scroll bar, if requested.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static int SetScrollInfo(
	SafeHandle hWnd,
	ScrollBarOrientation bar,
	ref ScrollInfo refScrollInfo,
	bool redraw
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetScrollInfo ( 
	hWnd As SafeHandle,
	bar As ScrollBarOrientation,
	ByRef refScrollInfo As ScrollInfo,
	redraw As Boolean
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim bar As ScrollBarOrientation
Dim refScrollInfo As ScrollInfo
Dim redraw As Boolean
Dim returnValue As Integer

returnValue = NativeMethods.SetScrollInfo(hWnd, 
	bar, refScrollInfo, redraw)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static int SetScrollInfo(
	SafeHandle^ hWnd, 
	ScrollBarOrientation bar, 
	ScrollInfo% refScrollInfo, 
	bool redraw
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetScrollInfo : 
        hWnd : SafeHandle * 
        bar : ScrollBarOrientation * 
        refScrollInfo : ScrollInfo byref * 
        redraw : bool -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to a scroll bar control or a window with a standard scroll bar, depending on the value of the *bar* parameter.</dd><dt>bar</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ScrollBarOrientation">DevCase.Interop.Unmanaged.Win32.Enums.ScrollBarOrientation</a><br />Specifies the type of scroll bar for which to set parameters.</dd><dt>refScrollInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo">DevCase.Interop.Unmanaged.Win32.Structures.ScrollInfo</a><br />Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo">ScrollInfo</a> structure. 

 Before calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetScrollInfo">SetScrollInfo(IntPtr, ScrollBarOrientation, ScrollInfo, Boolean)</a>, set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_SizeOfStruct">SizeOfStruct</a> member to `Marshal.SizeOf(Of ScrollInfo)`, and set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Mask">Mask</a> member to specify the scroll bar parameters to set, and specify the new parameter values in the appropriate members</dd><dt>redraw</dt><dd>Type: System.Boolean<br />Specifies whether the scroll bar is redrawn to reflect the changes to the scroll bar. 

 If this parameter is `true` (`True` in Visual Basic), the scroll bar is redrawn, otherwise, it is not redrawn.</dd></dl>

#### Return Value
Type: Int32<br />The return value is the current position of the scroll box.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/bb787595%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/bb787595%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetScrollInfo">SetScrollInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />