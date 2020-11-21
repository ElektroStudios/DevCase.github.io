# NativeMethods.GetPolyFillMode Method 
 

Retrieves the current polygon fill mode.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static FillMode GetPolyFillMode(
	IntPtr hDc
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function GetPolyFillMode ( 
	hDc As IntPtr
) As FillMode
```

**VB Usage**<br />
``` VB Usage
Dim hDc As IntPtr
Dim returnValue As FillMode

returnValue = NativeMethods.GetPolyFillMode(hDc)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static FillMode GetPolyFillMode(
	IntPtr hDc
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member GetPolyFillMode : 
        hDc : IntPtr -> FillMode 

```


#### Parameters
&nbsp;<dl><dt>hDc</dt><dd>Type: System.IntPtr<br />Handle to the device context.</dd></dl>

#### Return Value
Type: FillMode<br />If the function succeeds, the return value specifies the polygon fill mode. 

 If an error occurs, the return value is Alternate.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-getpolyfillmode" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-getpolyfillmode</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />