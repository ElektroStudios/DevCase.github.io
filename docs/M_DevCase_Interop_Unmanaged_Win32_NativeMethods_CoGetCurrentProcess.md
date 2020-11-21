# NativeMethods.CoGetCurrentProcess Method 
 

Returns a value that is unique to the current thread. 

CoGetCurrentProcess() can be used to avoid thread ID reuse problems.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", ExactSpelling = true)]
public static uint CoGetCurrentProcess()
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", ExactSpelling := true>]
Public Shared Function CoGetCurrentProcess As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.CoGetCurrentProcess()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", ExactSpelling = true)]
static unsigned int CoGetCurrentProcess()
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", ExactSpelling = true)>]
static member CoGetCurrentProcess : unit -> uint32 

```


#### Return Value
Type: UInt32<br />The function returns the unique identifier of the current thread.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cogetcurrentprocess" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cogetcurrentprocess</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />