# NativeMethods.FrameRect Method (IntPtr, NativeRectangle, IntPtr)
 

Draws a border around the specified rectangle by using the specified brush. 

 The width and height of the border are always one logical unit.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool FrameRect(
	IntPtr hDC,
	ref NativeRectangle refRect,
	IntPtr hBrush
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function FrameRect ( 
	hDC As IntPtr,
	ByRef refRect As NativeRectangle,
	hBrush As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDC As IntPtr
Dim refRect As NativeRectangle
Dim hBrush As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.FrameRect(hDC, 
	refRect, hBrush)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool FrameRect(
	IntPtr hDC, 
	NativeRectangle% refRect, 
	IntPtr hBrush
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member FrameRect : 
        hDC : IntPtr * 
        refRect : NativeRectangle byref * 
        hBrush : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDC</dt><dd>Type: System.IntPtr<br />A handle to the device context in which the border is drawn.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> that contains the logical coordinates of the upper-left and lower-right corners of the rectangle.</dd><dt>hBrush</dt><dd>Type: System.IntPtr<br />A handle to the brush used to draw the border.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-framerect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-framerect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_FrameRect">FrameRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />