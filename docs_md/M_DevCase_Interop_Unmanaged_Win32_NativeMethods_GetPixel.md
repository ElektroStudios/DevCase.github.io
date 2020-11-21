# NativeMethods.GetPixel Method (IntPtr, Int32, Int32)
 

Retrieves the Red, Green, Blue (RGB) color value of the pixel at the specified coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll")]
public static uint GetPixel(
	IntPtr hdc,
	int nXPos,
	int nYPos
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll">]
Public Shared Function GetPixel ( 
	hdc As IntPtr,
	nXPos As Integer,
	nYPos As Integer
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hdc As IntPtr
Dim nXPos As Integer
Dim nYPos As Integer
Dim returnValue As UInteger

returnValue = NativeMethods.GetPixel(hdc, 
	nXPos, nYPos)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll")]
static unsigned int GetPixel(
	IntPtr hdc, 
	int nXPos, 
	int nYPos
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll")>]
static member GetPixel : 
        hdc : IntPtr * 
        nXPos : int * 
        nYPos : int -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.IntPtr<br />A IntPtr handle to the device context.</dd><dt>nXPos</dt><dd>Type: System.Int32<br />The x-coordinate, in logical units, of the pixel to be examined.</dd><dt>nYPos</dt><dd>Type: System.Int32<br />The y-coordinate, in logical units, of the pixel to be examined.</dd></dl>

#### Return Value
Type: UInt32<br />The return value is the `COLORREF` value that specifies the RGB of the pixel. If the pixel is outside of the current clipping region, the return value is `CLR_INVALID` (`&HFFFFFFFF`)

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd144909%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd144909%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetPixel">GetPixel Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />