# NativeMethods.GetCurrentThreadStackLimits Method 
 

Retrieves the boundaries of the stack that was allocated by the system for the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static void GetCurrentThreadStackLimits(
	out UIntPtr refLowLimit,
	out UIntPtr refHighLimit
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Sub GetCurrentThreadStackLimits ( 
	<OutAttribute> ByRef refLowLimit As UIntPtr,
	<OutAttribute> ByRef refHighLimit As UIntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim refLowLimit As UIntPtr
Dim refHighLimit As UIntPtrNativeMethods.GetCurrentThreadStackLimits(refLowLimit, 
	refHighLimit)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static void GetCurrentThreadStackLimits(
	[OutAttribute] UIntPtr% refLowLimit, 
	[OutAttribute] UIntPtr% refHighLimit
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetCurrentThreadStackLimits : 
        refLowLimit : UIntPtr byref * 
        refHighLimit : UIntPtr byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refLowLimit</dt><dd>Type: System.UIntPtr<br />A pointer variable that receives the lower boundary of the current thread stack.</dd><dt>refHighLimit</dt><dd>Type: System.UIntPtr<br />A pointer variable that receives the upper boundary of the current thread stack.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getcurrentthreadstacklimits" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getcurrentthreadstacklimits</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />