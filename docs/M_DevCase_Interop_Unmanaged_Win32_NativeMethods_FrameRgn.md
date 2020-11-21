# NativeMethods.FrameRgn Method 
 

Draws a border around the specified region by using the specified brush.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static bool FrameRgn(
	IntPtr hDc,
	IntPtr hRgn,
	IntPtr hBrush,
	int width,
	int height
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function FrameRgn ( 
	hDc As IntPtr,
	hRgn As IntPtr,
	hBrush As IntPtr,
	width As Integer,
	height As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDc As IntPtr
Dim hRgn As IntPtr
Dim hBrush As IntPtr
Dim width As Integer
Dim height As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.FrameRgn(hDc, 
	hRgn, hBrush, width, height)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static bool FrameRgn(
	IntPtr hDc, 
	IntPtr hRgn, 
	IntPtr hBrush, 
	int width, 
	int height
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member FrameRgn : 
        hDc : IntPtr * 
        hRgn : IntPtr * 
        hBrush : IntPtr * 
        width : int * 
        height : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDc</dt><dd>Type: System.IntPtr<br />Handle to the device context.</dd><dt>hRgn</dt><dd>Type: System.IntPtr<br />Handle to the region to be enclosed in a border. 

 The region's coordinates are presumed to be in logical units.</dd><dt>hBrush</dt><dd>Type: System.IntPtr<br />Handle to the brush to be used to draw the border.</dd><dt>width</dt><dd>Type: System.Int32<br />Specifies the width, in logical units, of vertical brush strokes.</dd><dt>height</dt><dd>Type: System.Int32<br />Specifies the height, in logical units, of horizontal brush strokes.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-framergn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-framergn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />