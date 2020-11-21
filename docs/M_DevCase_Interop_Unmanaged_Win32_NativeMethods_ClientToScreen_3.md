# NativeMethods.ClientToScreen Method (SafeHandle, Point)
 

Converts the client-area coordinates of a specified point to screen coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool ClientToScreen(
	SafeHandle hWnd,
	ref Point refPoint
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function ClientToScreen ( 
	hWnd As SafeHandle,
	ByRef refPoint As Point
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refPoint As Point
Dim returnValue As Boolean

returnValue = NativeMethods.ClientToScreen(hWnd, 
	refPoint)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool ClientToScreen(
	SafeHandle^ hWnd, 
	Point% refPoint
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member ClientToScreen : 
        hWnd : SafeHandle * 
        refPoint : Point byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window whose client area is used for the conversion.</dd><dt>refPoint</dt><dd>Type: System.Drawing.Point<br />A pointer to a Point structure that contains the client coordinates to be converted. 

 The new screen coordinates are copied into this structure if the function succeeds.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183434%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183434%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ClientToScreen">ClientToScreen Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />