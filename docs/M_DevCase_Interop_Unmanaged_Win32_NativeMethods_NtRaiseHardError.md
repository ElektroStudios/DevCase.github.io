# NativeMethods.NtRaiseHardError Method 
 

This function sends HARDERROR_MSG LPC message to listener (typically CSRSS.EXE). 

 This function is called to cause a BSOD (Blue Screen of Death) with specific information.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", SetLastError = true)]
public static uint NtRaiseHardError(
	NTStatus errorStatus,
	uint numberOfParameters,
	uint unicodeStringParameterMask,
	IntPtr parameters,
	HardErrorResponseOption validResponseOption,
	ref HardErrorResponse refResponse
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", SetLastError := true>]
Public Shared Function NtRaiseHardError ( 
	errorStatus As NTStatus,
	numberOfParameters As UInteger,
	unicodeStringParameterMask As UInteger,
	parameters As IntPtr,
	validResponseOption As HardErrorResponseOption,
	ByRef refResponse As HardErrorResponse
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim errorStatus As NTStatus
Dim numberOfParameters As UInteger
Dim unicodeStringParameterMask As UInteger
Dim parameters As IntPtr
Dim validResponseOption As HardErrorResponseOption
Dim refResponse As HardErrorResponse
Dim returnValue As UInteger

returnValue = NativeMethods.NtRaiseHardError(errorStatus, 
	numberOfParameters, unicodeStringParameterMask, 
	parameters, validResponseOption, 
	refResponse)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", SetLastError = true)]
static unsigned int NtRaiseHardError(
	NTStatus errorStatus, 
	unsigned int numberOfParameters, 
	unsigned int unicodeStringParameterMask, 
	IntPtr parameters, 
	HardErrorResponseOption validResponseOption, 
	HardErrorResponse% refResponse
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", SetLastError = true)>]
static member NtRaiseHardError : 
        errorStatus : NTStatus * 
        numberOfParameters : uint32 * 
        unicodeStringParameterMask : uint32 * 
        parameters : IntPtr * 
        validResponseOption : HardErrorResponseOption * 
        refResponse : HardErrorResponse byref -> uint32 

```


#### Parameters
&nbsp;<dl><dt>errorStatus</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">DevCase.Interop.Unmanaged.Win32.Enums.NTStatus</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code.</dd><dt>numberOfParameters</dt><dd>Type: System.UInt32<br />Number of optional parameters in *parameters* array.</dd><dt>unicodeStringParameterMask</dt><dd>Type: System.UInt32<br />Optional string parameter (can be only one per error code).</dd><dt>parameters</dt><dd>Type: System.IntPtr<br />Array of parameters for use in error message string.</dd><dt>validResponseOption</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HardErrorResponseOption">DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponseOption</a><br />Specifies the response option.</dd><dt>refResponse</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HardErrorResponse">DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse</a><br />Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HardErrorResponse">HardErrorResponse</a> enumeration.</dd></dl>

#### Return Value
Type: UInt32<br />(Not documented)

## Remarks
<a href="https://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FError%2FNtRaiseHardError.html" target="_blank">https://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FError%2FNtRaiseHardError.html</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />