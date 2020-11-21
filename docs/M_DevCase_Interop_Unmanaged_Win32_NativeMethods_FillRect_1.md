# NativeMethods.FillRect Method (IntPtr, Rectangle, IntPtr)
 

Fills a rectangle by using the specified brush. 

 This function includes the left and top borders, but excludes the right and bottom borders of the rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool FillRect(
	IntPtr hDC,
	ref Rectangle refRect,
	IntPtr hBrush
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function FillRect ( 
	hDC As IntPtr,
	ByRef refRect As Rectangle,
	hBrush As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDC As IntPtr
Dim refRect As Rectangle
Dim hBrush As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.FillRect(hDC, 
	refRect, hBrush)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool FillRect(
	IntPtr hDC, 
	Rectangle% refRect, 
	IntPtr hBrush
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member FillRect : 
        hDC : IntPtr * 
        refRect : Rectangle byref * 
        hBrush : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDC</dt><dd>Type: System.IntPtr<br />A handle to the device context.</dd><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle that contains the logical coordinates of the rectangle to be filled.</dd><dt>hBrush</dt><dd>Type: System.IntPtr<br />A handle to the brush used to fill the rectangle.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-fillrect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-fillrect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_FillRect">FillRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />