# NativeMethods.SetPolyFillMode Method 
 

Sets the polygon fill mode for functions that fill polygons.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static FillMode SetPolyFillMode(
	IntPtr hDc,
	FillMode mode
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function SetPolyFillMode ( 
	hDc As IntPtr,
	mode As FillMode
) As FillMode
```

**VB Usage**<br />
``` VB Usage
Dim hDc As IntPtr
Dim mode As FillMode
Dim returnValue As FillMode

returnValue = NativeMethods.SetPolyFillMode(hDc, 
	mode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static FillMode SetPolyFillMode(
	IntPtr hDc, 
	FillMode mode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member SetPolyFillMode : 
        hDc : IntPtr * 
        mode : FillMode -> FillMode 

```


#### Parameters
&nbsp;<dl><dt>hDc</dt><dd>Type: System.IntPtr<br />A handle to the device context.</dd><dt>mode</dt><dd>Type: System.Drawing.Drawing2D.FillMode<br />The new fill mode.</dd></dl>

#### Return Value
Type: FillMode<br />The return value specifies the previous filling mode. 

 If an error occurs, the return value is Alternate.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-setpolyfillmode" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-setpolyfillmode</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />