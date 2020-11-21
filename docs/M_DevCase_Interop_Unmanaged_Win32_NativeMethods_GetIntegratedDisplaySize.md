# NativeMethods.GetIntegratedDisplaySize Method 
 

Retrieves the best estimate of the diagonal size of the built-in screen, in inches.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static HResult GetIntegratedDisplaySize(
	out double refSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetIntegratedDisplaySize ( 
	<OutAttribute> ByRef refSize As Double
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refSize As Double
Dim returnValue As HResult

returnValue = NativeMethods.GetIntegratedDisplaySize(refSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static HResult GetIntegratedDisplaySize(
	[OutAttribute] double% refSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetIntegratedDisplaySize : 
        refSize : float byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refSize</dt><dd>Type: System.Double<br />The best estimate of the diagonal size of the built-in screen, in inches.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If successful, returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 If not successful, returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getintegrateddisplaysize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getintegrateddisplaysize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />