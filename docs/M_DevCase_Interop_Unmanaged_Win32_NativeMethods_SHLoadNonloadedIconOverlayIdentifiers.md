# NativeMethods.SHLoadNonloadedIconOverlayIdentifiers Method 
 

Signals the Shell that during the next operation requiring overlay information, it should load icon overlay identifiers that either failed creation or were not present for creation at startup. 

 Identifiers that have already been loaded are not affected.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static HResult SHLoadNonloadedIconOverlayIdentifiers()
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function SHLoadNonloadedIconOverlayIdentifiers As HResult
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As HResult

returnValue = NativeMethods.SHLoadNonloadedIconOverlayIdentifiers()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static HResult SHLoadNonloadedIconOverlayIdentifiers()
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member SHLoadNonloadedIconOverlayIdentifiers : unit -> HResult 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Always returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-shloadnonloadediconoverlayidentifiers" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-shloadnonloadediconoverlayidentifiers</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />