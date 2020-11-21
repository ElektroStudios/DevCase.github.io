# NativeMethods.ShowScrollBar Method (SafeHandle, ScrollBarOrientation, Boolean)
 

Shows or hides the specified scrollbar of a Control/Window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool ShowScrollBar(
	SafeHandle hWnd,
	ScrollBarOrientation bar,
	bool show
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ShowScrollBar ( 
	hWnd As SafeHandle,
	bar As ScrollBarOrientation,
	show As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim bar As ScrollBarOrientation
Dim show As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.ShowScrollBar(hWnd, 
	bar, show)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool ShowScrollBar(
	SafeHandle^ hWnd, 
	ScrollBarOrientation bar, 
	bool show
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ShowScrollBar : 
        hWnd : SafeHandle * 
        bar : ScrollBarOrientation * 
        show : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to a scrollbar control or a window with a standard scrollbar, depending on the value of the *bar* parameter.</dd><dt>bar</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ScrollBarOrientation">DevCase.Interop.Unmanaged.Win32.Enums.ScrollBarOrientation</a><br />Specifies the scrollbar(s) to be shown or hidden.</dd><dt>show</dt><dd>Type: System.Boolean<br />Specifies whether the scroll bar is shown or hidden. 

 If this parameter is `true` (`True` in Visual Basic), the scroll bar is shown; otherwise, it is hidden.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) If the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb787601%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb787601%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShowScrollBar">ShowScrollBar Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />