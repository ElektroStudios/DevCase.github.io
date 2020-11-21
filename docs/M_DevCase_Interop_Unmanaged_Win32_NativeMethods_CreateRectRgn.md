# NativeMethods.CreateRectRgn Method 
 

Creates a rectangular region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static IntPtr CreateRectRgn(
	int x1,
	int y1,
	int x2,
	int y2
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function CreateRectRgn ( 
	x1 As Integer,
	y1 As Integer,
	x2 As Integer,
	y2 As Integer
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim x1 As Integer
Dim y1 As Integer
Dim x2 As Integer
Dim y2 As Integer
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateRectRgn(x1, 
	y1, x2, y2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static IntPtr CreateRectRgn(
	int x1, 
	int y1, 
	int x2, 
	int y2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member CreateRectRgn : 
        x1 : int * 
        y1 : int * 
        x2 : int * 
        y2 : int -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>x1</dt><dd>Type: System.Int32<br />Specifies the x-coordinate of the upper-left corner of the region in logical units.</dd><dt>y1</dt><dd>Type: System.Int32<br />Specifies the y-coordinate of the upper-left corner of the region in logical units.</dd><dt>x2</dt><dd>Type: System.Int32<br />Specifies the x-coordinate of the lower-right corner of the region in logical units.</dd><dt>y2</dt><dd>Type: System.Int32<br />Specifies the y-coordinate of the lower-right corner of the region in logical units.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the region. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createrectrgn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createrectrgn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />