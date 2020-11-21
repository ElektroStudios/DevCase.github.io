# NativeMethods.CoUninitialize Method 
 

Closes the COM library on the current thread, unloads all DLLs loaded by the thread, frees any other resources that the thread maintains, and forces all RPC connections on the thread to close.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", CallingConvention = CallingConvention.StdCall, 
	ExactSpelling = true)]
public static void CoUninitialize()
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", CallingConvention := CallingConvention.StdCall, 
	ExactSpelling := true>]
Public Shared Sub CoUninitialize
```

**VB Usage**<br />
``` VB Usage

NativeMethods.CoUninitialize()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", CallingConvention = CallingConvention::StdCall, 
	ExactSpelling = true)]
static void CoUninitialize()
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", CallingConvention = CallingConvention.StdCall, 
	ExactSpelling = true)>]
static member CoUninitialize : unit -> unit 

```


## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-couninitialize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-couninitialize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />