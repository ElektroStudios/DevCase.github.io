# NativeMethods.CreatePolygonRgn Method (NativePoint, Int32, FillMode)
 

Creates a polygonal region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static IntPtr CreatePolygonRgn(
	NativePoint ptArray,
	int ptCount,
	FillMode mode
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function CreatePolygonRgn ( 
	ptArray As NativePoint,
	ptCount As Integer,
	mode As FillMode
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim ptArray As NativePoint
Dim ptCount As Integer
Dim mode As FillMode
Dim returnValue As IntPtr

returnValue = NativeMethods.CreatePolygonRgn(ptArray, 
	ptCount, mode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static IntPtr CreatePolygonRgn(
	NativePoint ptArray, 
	int ptCount, 
	FillMode mode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member CreatePolygonRgn : 
        ptArray : NativePoint * 
        ptCount : int * 
        mode : FillMode -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>ptArray</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> structures that define the vertices of the polygon in logical units. The polygon is presumed closed. 

 Each vertex can be specified only once.</dd><dt>ptCount</dt><dd>Type: System.Int32<br />The number of points in the array.</dd><dt>mode</dt><dd>Type: System.Drawing.Drawing2D.FillMode<br />The fill mode used to determine which pixels are in the region.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the region. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createpolygonrgn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createpolygonrgn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreatePolygonRgn">CreatePolygonRgn Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />