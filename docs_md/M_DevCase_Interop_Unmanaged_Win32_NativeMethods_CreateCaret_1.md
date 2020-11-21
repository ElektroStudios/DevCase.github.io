# NativeMethods.CreateCaret Method (SafeHandle, IntPtr, Int32, Int32)
 

Creates a new shape for the system caret and assigns ownership of the caret to the specified window. 

 The caret shape can be a line, a block, or a bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool CreateCaret(
	SafeHandle hWnd,
	IntPtr bitmap,
	int width,
	int nHeight
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function CreateCaret ( 
	hWnd As SafeHandle,
	bitmap As IntPtr,
	width As Integer,
	nHeight As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim bitmap As IntPtr
Dim width As Integer
Dim nHeight As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.CreateCaret(hWnd, 
	bitmap, width, nHeight)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool CreateCaret(
	SafeHandle^ hWnd, 
	IntPtr bitmap, 
	int width, 
	int nHeight
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member CreateCaret : 
        hWnd : SafeHandle * 
        bitmap : IntPtr * 
        width : int * 
        nHeight : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window that owns the caret.</dd><dt>bitmap</dt><dd>Type: System.IntPtr<br />A handle to the bitmap that defines the caret shape. 

 If this parameter is Zero, the caret is solid. 

 If this parameter is (`HBITMAP`) `New IntPtr(1)`, the caret is gray. 

 If this parameter is a bitmap handle, the caret is the specified bitmap. 

 The bitmap handle must have been created by the `CreateBitmap`, `CreateDIBitmap`, or `LoadBitmap` function.</dd><dt>width</dt><dd>Type: System.Int32<br />The width of the caret, in logical units. 

 If this parameter is zero, the width is set to the system-defined window border width. 

 If `hBitmap` is a bitmap handle, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateCaret">CreateCaret(IntPtr, IntPtr, Int32, Int32)</a> ignores this parameter.</dd><dt>nHeight</dt><dd>Type: System.Int32<br />The height of the caret, in logical units. 

 If this parameter is zero, the height is set to the system-defined window border height. 

 If `hBitmap` is a bitmap handle, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateCaret">CreateCaret(IntPtr, IntPtr, Int32, Int32)</a> ignores this parameter.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648399%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648399%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateCaret">CreateCaret Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />