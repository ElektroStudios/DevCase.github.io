# NativeMethods.FillRgn Method 
 

Fills a region by using the specified brush.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static bool FillRgn(
	IntPtr hDc,
	IntPtr hRgn,
	IntPtr hBrush
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function FillRgn ( 
	hDc As IntPtr,
	hRgn As IntPtr,
	hBrush As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDc As IntPtr
Dim hRgn As IntPtr
Dim hBrush As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.FillRgn(hDc, hRgn, 
	hBrush)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static bool FillRgn(
	IntPtr hDc, 
	IntPtr hRgn, 
	IntPtr hBrush
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member FillRgn : 
        hDc : IntPtr * 
        hRgn : IntPtr * 
        hBrush : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDc</dt><dd>Type: System.IntPtr<br />Handle to the device context.</dd><dt>hRgn</dt><dd>Type: System.IntPtr<br />Handle to the region to be filled. 

 The region's coordinates are presumed to be in logical units.</dd><dt>hBrush</dt><dd>Type: System.IntPtr<br />Handle to the brush to be used to fill the region.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-fillrgn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-fillrgn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />