# NativeMethods.CreatePolyPolygonRgn Method (NativePoint[], Int32[], Int32, FillMode)
 

Creates a region consisting of a series of polygons. The polygons can overlap.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static IntPtr CreatePolyPolygonRgn(
	NativePoint[] ptArray,
	int[] intArray,
	int intCount,
	FillMode mode
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function CreatePolyPolygonRgn ( 
	ptArray As NativePoint(),
	intArray As Integer(),
	intCount As Integer,
	mode As FillMode
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim ptArray As NativePoint()
Dim intArray As Integer()
Dim intCount As Integer
Dim mode As FillMode
Dim returnValue As IntPtr

returnValue = NativeMethods.CreatePolyPolygonRgn(ptArray, 
	intArray, intCount, mode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static IntPtr CreatePolyPolygonRgn(
	[InAttribute] array<NativePoint>^ ptArray, 
	[InAttribute] array<int>^ intArray, 
	int intCount, 
	FillMode mode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member CreatePolyPolygonRgn : 
        ptArray : NativePoint[] * 
        intArray : int[] * 
        intCount : int * 
        mode : FillMode -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>ptArray</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a>[]<br />An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> structures that define the vertices of the polygons in logical units. The polygons are specified consecutively. 

 Each polygon is presumed closed and each vertex is specified only once.</dd><dt>intArray</dt><dd>Type: System.Int32[]<br />An array of integers, each of which specifies the number of points in one of the polygons in the array pointed to by *ptArray*.</dd><dt>intCount</dt><dd>Type: System.Int32<br />The total number of integers in the array pointed to by *intArray*.</dd><dt>mode</dt><dd>Type: System.Drawing.Drawing2D.FillMode<br />The fill mode used to determine which pixels are in the region.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the region. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createpolypolygonrgn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createpolypolygonrgn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreatePolyPolygonRgn">CreatePolyPolygonRgn Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />