# NativeMethods.GetWindowRect Method (SafeHandle, Rectangle)
 

Retrieves the dimensions of the bounding rectangle of the specified window. 

 The dimensions are given in screen coordinates that are relative to the upper-left corner of the screen.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetWindowRect(
	SafeHandle hWnd,
	out Rectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindowRect ( 
	hWnd As SafeHandle,
	<OutAttribute> ByRef refRect As Rectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refRect As Rectangle
Dim returnValue As Boolean

returnValue = NativeMethods.GetWindowRect(hWnd, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetWindowRect(
	SafeHandle^ hWnd, 
	[OutAttribute] Rectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindowRect : 
        hWnd : SafeHandle * 
        refRect : Rectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A IntPtr handle to the window.</dd><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to a Rectangle structure that receives the screen coordinates of the upper-left and lower-right corners of the window.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms633519%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms633519%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowRect">GetWindowRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />