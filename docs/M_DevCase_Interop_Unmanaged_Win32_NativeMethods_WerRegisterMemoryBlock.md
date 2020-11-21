# NativeMethods.WerRegisterMemoryBlock Method 
 

Registers a memory block to be collected when WER creates an error report.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static HResult WerRegisterMemoryBlock(
	IntPtr address,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function WerRegisterMemoryBlock ( 
	address As IntPtr,
	size As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim size As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.WerRegisterMemoryBlock(address, 
	size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static HResult WerRegisterMemoryBlock(
	IntPtr address, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member WerRegisterMemoryBlock : 
        address : IntPtr * 
        size : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />The starting address of the memory block.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size of the memory block, in bytes. 

 The maximum value for this parameter is WER_MAX_MEM_BLOCK_SIZE bytes.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregistermemoryblock" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregistermemoryblock</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />