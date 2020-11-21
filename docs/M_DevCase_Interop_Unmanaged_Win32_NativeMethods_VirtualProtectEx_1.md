# NativeMethods.VirtualProtectEx Method (IntPtr, IntPtr, UIntPtr, MemoryProtectionOptions, MemoryProtectionOptions)
 

Changes the protection on a region of committed pages in the virtual address space of a specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool VirtualProtectEx(
	IntPtr hProcess,
	IntPtr address,
	UIntPtr size,
	MemoryProtectionOptions newProtect,
	out MemoryProtectionOptions refOldProtect
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function VirtualProtectEx ( 
	hProcess As IntPtr,
	address As IntPtr,
	size As UIntPtr,
	newProtect As MemoryProtectionOptions,
	<OutAttribute> ByRef refOldProtect As MemoryProtectionOptions
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim address As IntPtr
Dim size As UIntPtr
Dim newProtect As MemoryProtectionOptions
Dim refOldProtect As MemoryProtectionOptions
Dim returnValue As Boolean

returnValue = NativeMethods.VirtualProtectEx(hProcess, 
	address, size, newProtect, refOldProtect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool VirtualProtectEx(
	[InAttribute] IntPtr hProcess, 
	[InAttribute] IntPtr address, 
	UIntPtr size, 
	MemoryProtectionOptions newProtect, 
	[OutAttribute] MemoryProtectionOptions% refOldProtect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member VirtualProtectEx : 
        hProcess : IntPtr * 
        address : IntPtr * 
        size : UIntPtr * 
        newProtect : MemoryProtectionOptions * 
        refOldProtect : MemoryProtectionOptions byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process whose memory protection is to be changed. The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a> access right.</dd><dt>address</dt><dd>Type: System.IntPtr<br />A pointer an address that describes the starting page of the region of pages whose access protection attributes are to be changed. 

 All pages in the specified region must be within the same reserved region allocated when calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function using <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">Reserve</a> flag. 

 The pages cannot span adjacent reserved regions that were allocated by separate calls to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function using <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">Reserve</a> flag.</dd><dt>size</dt><dd>Type: System.UIntPtr<br />The size of the region whose access protection attributes are to be changed, in bytes. 

 The region of affected pages includes all pages containing one or more bytes in the range from the *address* parameter to (*address*+*size*). 

 This means that a 2-byte range straddling a page boundary causes the protection attributes of both pages to be changed.</dd><dt>newProtect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions</a><br />The memory protection option.</dd><dt>refOldProtect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions</a><br />A pointer to a variable that receives the previous memory protection option value of the first page in the specified region of pages. 

 If this parameter is a null reference (`Nothing` in Visual Basic) or does not point to a valid variable, the function fails.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-virtualprotectex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-virtualprotectex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualProtectEx">VirtualProtectEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />