# NativeMethods.SetBkMode Method 
 

Sts the background mix mode of the specified device context (DC). 

 The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", ExactSpelling = true, SetLastError = true)]
public static BackgroundMode SetBkMode(
	IntPtr hdc,
	BackgroundMode mode
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetBkMode ( 
	hdc As IntPtr,
	mode As BackgroundMode
) As BackgroundMode
```

**VB Usage**<br />
``` VB Usage
Dim hdc As IntPtr
Dim mode As BackgroundMode
Dim returnValue As BackgroundMode

returnValue = NativeMethods.SetBkMode(hdc, 
	mode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", ExactSpelling = true, SetLastError = true)]
static BackgroundMode SetBkMode(
	IntPtr hdc, 
	BackgroundMode mode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetBkMode : 
        hdc : IntPtr * 
        mode : BackgroundMode -> BackgroundMode 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.IntPtr<br />A handle to the device context.</dd><dt>mode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BackgroundMode">DevCase.Interop.Unmanaged.Win32.Enums.BackgroundMode</a><br />The background mode.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BackgroundMode">BackgroundMode</a><br />If the function succeeds, the return value specifies the previous background mode. 

 If the function fails, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BackgroundMode">ERROR</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-setbkmode" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-setbkmode</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />