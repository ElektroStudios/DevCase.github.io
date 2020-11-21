# NativeMethods.UpdateLayeredWindow Method (SafeHandle, IntPtr, NativePoint, NativeSize, IntPtr, NativePoint, Int32, BlendFunction, UpdateLayeredWindowflags)
 

Updates the position, size, shape, content, and translucency of a layered window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool UpdateLayeredWindow(
	SafeHandle hWnd,
	IntPtr hdcDst,
	ref NativePoint refPtrDst,
	ref NativeSize refSize,
	IntPtr hdcSrc,
	ref NativePoint refPtrSrc,
	int crKey,
	ref BlendFunction refBlend,
	UpdateLayeredWindowflags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function UpdateLayeredWindow ( 
	hWnd As SafeHandle,
	hdcDst As IntPtr,
	ByRef refPtrDst As NativePoint,
	ByRef refSize As NativeSize,
	hdcSrc As IntPtr,
	ByRef refPtrSrc As NativePoint,
	crKey As Integer,
	ByRef refBlend As BlendFunction,
	flags As UpdateLayeredWindowflags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim hdcDst As IntPtr
Dim refPtrDst As NativePoint
Dim refSize As NativeSize
Dim hdcSrc As IntPtr
Dim refPtrSrc As NativePoint
Dim crKey As Integer
Dim refBlend As BlendFunction
Dim flags As UpdateLayeredWindowflags
Dim returnValue As Boolean

returnValue = NativeMethods.UpdateLayeredWindow(hWnd, 
	hdcDst, refPtrDst, refSize, hdcSrc, 
	refPtrSrc, crKey, refBlend, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool UpdateLayeredWindow(
	SafeHandle^ hWnd, 
	IntPtr hdcDst, 
	NativePoint% refPtrDst, 
	NativeSize% refSize, 
	IntPtr hdcSrc, 
	NativePoint% refPtrSrc, 
	int crKey, 
	BlendFunction% refBlend, 
	UpdateLayeredWindowflags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member UpdateLayeredWindow : 
        hWnd : SafeHandle * 
        hdcDst : IntPtr * 
        refPtrDst : NativePoint byref * 
        refSize : NativeSize byref * 
        hdcSrc : IntPtr * 
        refPtrSrc : NativePoint byref * 
        crKey : int * 
        refBlend : BlendFunction byref * 
        flags : UpdateLayeredWindowflags -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to a layered window. 

 A layered window is created by specifying <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStylesEx">Layered</a> when creating the window with the `CreateWindowEx` function or by setting <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStylesEx">Layered</a> via <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowLongPtr">SetWindowLongPtr(IntPtr, WindowLongValues, IntPtr)</a> function. after the window has been created.</dd><dt>hdcDst</dt><dd>Type: System.IntPtr<br />A handle to a device context (DC) for the screen. 

 This handle is obtained by specifying NULL when calling the function. 

 It is used for palette color matching when the window contents are updated. 

 If *hdcDst* is Zero, the default palette will be used.</dd><dt>refPtrDst</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />A pointer to a structure that specifies the new screen position of the layered window. 

 If the current position is not changing, *refPtrDst* can be Zero.</dd><dt>refSize</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">DevCase.Interop.Unmanaged.Win32.Structures.NativeSize</a><br />A pointer to a structure that specifies the new size of the layered window. 

 If the size of the window is not changing, *refSize* can be a null reference (`Nothing` in Visual Basic). 

 If *hdcSrc* is Zero, *refSize* must be a null reference (`Nothing` in Visual Basic).</dd><dt>hdcSrc</dt><dd>Type: System.IntPtr<br />A handle to a device context (DC) for the surface that defines the layered window. 

 This handle can be obtained by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateCompatibleDC">CreateCompatibleDC(IntPtr)</a> function. 

 If the shape and visual context of the window are not changing, *hdcSrc* can be Zero.</dd><dt>refPtrSrc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />A pointer to a structure that specifies the location of the layer in the device context. 

 If *hdcSrc* is Zero, `pptSrc` should be a null reference (`Nothing` in Visual Basic).</dd><dt>crKey</dt><dd>Type: System.Int32<br />A structure that specifies the color key to be used when composing the layered window. 

 To generate a `COLORREF`, use the `RGB` macro.</dd><dt>refBlend</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction">DevCase.Interop.Unmanaged.Win32.Structures.BlendFunction</a><br />A pointer to a structure that specifies the transparency value to be used when composing the layered window.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_UpdateLayeredWindowflags">DevCase.Interop.Unmanaged.Win32.Enums.UpdateLayeredWindowflags</a><br />The flags.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms633556%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms633556%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateLayeredWindow">UpdateLayeredWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />