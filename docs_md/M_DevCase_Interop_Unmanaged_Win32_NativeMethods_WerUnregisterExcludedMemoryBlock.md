# NativeMethods.WerUnregisterExcludedMemoryBlock Method 
 

Removes a memory block that was previously marked as excluded (it will again be included in error reports).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static HResult WerUnregisterExcludedMemoryBlock(
	IntPtr address
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function WerUnregisterExcludedMemoryBlock ( 
	address As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.WerUnregisterExcludedMemoryBlock(address)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static HResult WerUnregisterExcludedMemoryBlock(
	IntPtr address
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member WerUnregisterExcludedMemoryBlock : 
        address : IntPtr -> HResult 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />The starting address of the memory block. 

 This memory block must have been registered using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WerRegisterExcludedMemoryBlock">WerRegisterExcludedMemoryBlock(IntPtr, UInt32)</a> function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werunregisterexcludedmemoryblock" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werunregisterexcludedmemoryblock</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />