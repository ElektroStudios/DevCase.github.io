# NativeMethods.GetWindowRect Method (IntPtr, NativeRectangle)
 

Retrieves the dimensions of the bounding rectangle of the specified window. 

 The dimensions are given in screen coordinates that are relative to the upper-left corner of the screen.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetWindowRect(
	IntPtr hWnd,
	out NativeRectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindowRect ( 
	hWnd As IntPtr,
	<OutAttribute> ByRef refRect As NativeRectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim refRect As NativeRectangle
Dim returnValue As Boolean

returnValue = NativeMethods.GetWindowRect(hWnd, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetWindowRect(
	IntPtr hWnd, 
	[OutAttribute] NativeRectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindowRect : 
        hWnd : IntPtr * 
        refRect : NativeRectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A IntPtr handle to the window.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that receives the screen coordinates of the upper-left and lower-right corners of the window.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms633519%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms633519%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowRect">GetWindowRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />