# NativeMethods.CreateRoundRectRgn Method 
 

Creates a rectangular region with rounded corners.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll")]
public static IntPtr CreateRoundRectRgn(
	int leftRect,
	int topRect,
	int rightRect,
	int bottomRect,
	int widthEllipse,
	int heightEllipse
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll">]
Public Shared Function CreateRoundRectRgn ( 
	leftRect As Integer,
	topRect As Integer,
	rightRect As Integer,
	bottomRect As Integer,
	widthEllipse As Integer,
	heightEllipse As Integer
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim leftRect As Integer
Dim topRect As Integer
Dim rightRect As Integer
Dim bottomRect As Integer
Dim widthEllipse As Integer
Dim heightEllipse As Integer
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateRoundRectRgn(leftRect, 
	topRect, rightRect, bottomRect, widthEllipse, 
	heightEllipse)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll")]
static IntPtr CreateRoundRectRgn(
	int leftRect, 
	int topRect, 
	int rightRect, 
	int bottomRect, 
	int widthEllipse, 
	int heightEllipse
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll")>]
static member CreateRoundRectRgn : 
        leftRect : int * 
        topRect : int * 
        rightRect : int * 
        bottomRect : int * 
        widthEllipse : int * 
        heightEllipse : int -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>leftRect</dt><dd>Type: System.Int32<br />The x-coordinate of the upper-left corner of the region in device units.</dd><dt>topRect</dt><dd>Type: System.Int32<br />The y-coordinate of the upper-left corner of the region in device units.</dd><dt>rightRect</dt><dd>Type: System.Int32<br />The x-coordinate of the lower-right corner of the region in device units.</dd><dt>bottomRect</dt><dd>Type: System.Int32<br />The y-coordinate of the lower-right corner of the region in device units.</dd><dt>widthEllipse</dt><dd>Type: System.Int32<br />The width of the ellipse used to create the rounded corners in device units.</dd><dt>heightEllipse</dt><dd>Type: System.Int32<br />The height of the ellipse used to create the rounded corners in device units.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the region. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183516%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183516%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />