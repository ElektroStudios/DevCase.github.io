# NativeMethods.BitBlt Method (IntPtr, Int32, Int32, Int32, Int32, IntPtr, Int32, Int32, TernaryRasterOperations)
 

Performs a bit-block transfer of the color data corresponding to a rectangle of pixels from the specified source device context into a destination device context.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll")]
public static bool BitBlt(
	IntPtr hdc,
	int nXDest,
	int nYDest,
	int nWidth,
	int nHeight,
	IntPtr hdcSrc,
	int nXSrc,
	int nYSrc,
	TernaryRasterOperations dwRop
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll">]
Public Shared Function BitBlt ( 
	hdc As IntPtr,
	nXDest As Integer,
	nYDest As Integer,
	nWidth As Integer,
	nHeight As Integer,
	hdcSrc As IntPtr,
	nXSrc As Integer,
	nYSrc As Integer,
	dwRop As TernaryRasterOperations
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hdc As IntPtr
Dim nXDest As Integer
Dim nYDest As Integer
Dim nWidth As Integer
Dim nHeight As Integer
Dim hdcSrc As IntPtr
Dim nXSrc As Integer
Dim nYSrc As Integer
Dim dwRop As TernaryRasterOperations
Dim returnValue As Boolean

returnValue = NativeMethods.BitBlt(hdc, nXDest, 
	nYDest, nWidth, nHeight, hdcSrc, nXSrc, 
	nYSrc, dwRop)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll")]
static bool BitBlt(
	IntPtr hdc, 
	int nXDest, 
	int nYDest, 
	int nWidth, 
	int nHeight, 
	IntPtr hdcSrc, 
	int nXSrc, 
	int nYSrc, 
	TernaryRasterOperations dwRop
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll")>]
static member BitBlt : 
        hdc : IntPtr * 
        nXDest : int * 
        nYDest : int * 
        nWidth : int * 
        nHeight : int * 
        hdcSrc : IntPtr * 
        nXSrc : int * 
        nYSrc : int * 
        dwRop : TernaryRasterOperations -> bool 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.IntPtr<br />A handle to the destination device context.</dd><dt>nXDest</dt><dd>Type: System.Int32<br />The x-coordinate, in logical units, of the upper-left corner of the destination rectangle.</dd><dt>nYDest</dt><dd>Type: System.Int32<br />The y-coordinate, in logical units, of the upper-left corner of the destination rectangle.</dd><dt>nWidth</dt><dd>Type: System.Int32<br />The width, in logical units, of the source and destination rectangles.</dd><dt>nHeight</dt><dd>Type: System.Int32<br />The height, in logical units, of the source and the destination rectangles.</dd><dt>hdcSrc</dt><dd>Type: System.IntPtr<br />A handle to the source device context.</dd><dt>nXSrc</dt><dd>Type: System.Int32<br />The x-coordinate, in logical units, of the upper-left corner of the source rectangle.</dd><dt>nYSrc</dt><dd>Type: System.Int32<br />The y-coordinate, in logical units, of the upper-left corner of the source rectangle.</dd><dt>dwRop</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TernaryRasterOperations">DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations</a><br />A raster-operation code. These codes define how the color data for the source rectangle is to be combined with 

 the color data for the destination rectangle to achieve the final color.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic)

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd183370%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd183370%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_BitBlt">BitBlt Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />