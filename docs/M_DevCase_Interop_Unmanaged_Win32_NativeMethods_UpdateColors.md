# NativeMethods.UpdateColors Method 
 

Updates the client area of the specified device context by remapping the current colors in the client area to the currently realized logical palette.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static bool UpdateColors(
	IntPtr hDc
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function UpdateColors ( 
	hDc As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDc As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.UpdateColors(hDc)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static bool UpdateColors(
	IntPtr hDc
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member UpdateColors : 
        hDc : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDc</dt><dd>Type: System.IntPtr<br />A handle to the device context.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-updatecolors" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-updatecolors</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />