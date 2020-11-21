# NativeMethods.GetCurrentProcessorNumber Method 
 

Retrieves the number of the processor the current thread was running on during the call to this function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static uint GetCurrentProcessorNumber()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetCurrentProcessorNumber As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetCurrentProcessorNumber()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static unsigned int GetCurrentProcessorNumber()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetCurrentProcessorNumber : unit -> uint32 

```


#### Return Value
Type: UInt32<br />The function returns the current processor number.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getcurrentprocessornumber" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getcurrentprocessornumber</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />