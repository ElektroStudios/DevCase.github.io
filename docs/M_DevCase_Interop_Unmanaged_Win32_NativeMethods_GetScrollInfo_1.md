# NativeMethods.GetScrollInfo Method (SafeHandle, ScrollBarOrientation, ScrollInfo)
 

Retrieves the parameters of a scroll bar, including the minimum and maximum scrolling positions, the page size, and the position of the scroll box (thumb).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetScrollInfo(
	SafeHandle hWnd,
	ScrollBarOrientation bar,
	ref ScrollInfo refScrollInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetScrollInfo ( 
	hWnd As SafeHandle,
	bar As ScrollBarOrientation,
	ByRef refScrollInfo As ScrollInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim bar As ScrollBarOrientation
Dim refScrollInfo As ScrollInfo
Dim returnValue As Boolean

returnValue = NativeMethods.GetScrollInfo(hWnd, 
	bar, refScrollInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetScrollInfo(
	SafeHandle^ hWnd, 
	ScrollBarOrientation bar, 
	ScrollInfo% refScrollInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetScrollInfo : 
        hWnd : SafeHandle * 
        bar : ScrollBarOrientation * 
        refScrollInfo : ScrollInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to a scroll bar control or a window with a standard scroll bar, depending on the value of the *bar* parameter.</dd><dt>bar</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ScrollBarOrientation">DevCase.Interop.Unmanaged.Win32.Enums.ScrollBarOrientation</a><br />Specifies the type of scroll bar for which to retrieve parameters.</dd><dt>refScrollInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo">DevCase.Interop.Unmanaged.Win32.Structures.ScrollInfo</a><br />Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo">ScrollInfo</a> structure. 

 Before calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetScrollInfo">GetScrollInfo(IntPtr, ScrollBarOrientation, ScrollInfo)</a>, set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_SizeOfStruct">SizeOfStruct</a> member to `Marshal.SizeOf(Of ScrollInfo)`, and set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Mask">Mask</a> member to specify the scroll bar parameters to retrieve. 

 Before returning, the function copies the specified parameters to the appropriate members of the structure.</dd></dl>

#### Return Value
Type: Boolean<br />If the function retrieved any values, the return value is `true` (`True` in Visual Basic)

 If the function does not retrieve any values, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/bb787583%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/bb787583%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetScrollInfo">GetScrollInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />