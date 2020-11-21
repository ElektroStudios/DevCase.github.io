# NativeMethods.WerUnregisterRuntimeExceptionModule Method 
 

Removes the registration of your WER exception handler.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
public static HResult WerUnregisterRuntimeExceptionModule(
	string outOfProcessCallbackDll,
	IntPtr context
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
Public Shared Function WerUnregisterRuntimeExceptionModule ( 
	outOfProcessCallbackDll As String,
	context As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim outOfProcessCallbackDll As String
Dim context As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.WerUnregisterRuntimeExceptionModule(outOfProcessCallbackDll, 
	context)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
static HResult WerUnregisterRuntimeExceptionModule(
	String^ outOfProcessCallbackDll, 
	IntPtr context
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
static member WerUnregisterRuntimeExceptionModule : 
        outOfProcessCallbackDll : string * 
        context : IntPtr -> HResult 

```


#### Parameters
&nbsp;<dl><dt>outOfProcessCallbackDll</dt><dd>Type: System.String<br />The name of the exception handler DLL whose registration you want to remove.</dd><dt>context</dt><dd>Type: System.IntPtr<br />A pointer to arbitrary context information that was passed to the callback.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/werapi/nf-werapi-werunregisterruntimeexceptionmodule" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/werapi/nf-werapi-werunregisterruntimeexceptionmodule</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />