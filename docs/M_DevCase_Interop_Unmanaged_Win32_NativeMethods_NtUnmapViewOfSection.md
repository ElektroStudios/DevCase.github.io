# NativeMethods.NtUnmapViewOfSection Method (SafeProcessHandle, IntPtr)
 

Unmaps a view of a section from the virtual address space of a subject process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)]
public static NTStatus NtUnmapViewOfSection(
	SafeProcessHandle hProcess,
	IntPtr address
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", CallingConvention := CallingConvention.StdCall>]
Public Shared Function NtUnmapViewOfSection ( 
	hProcess As SafeProcessHandle,
	address As IntPtr
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As SafeProcessHandle
Dim address As IntPtr
Dim returnValue As NTStatus

returnValue = NativeMethods.NtUnmapViewOfSection(hProcess, 
	address)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", CallingConvention = CallingConvention::StdCall)]
static NTStatus NtUnmapViewOfSection(
	[InAttribute] SafeProcessHandle^ hProcess, 
	[InAttribute] IntPtr address
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)>]
static member NtUnmapViewOfSection : 
        hProcess : SafeProcessHandle * 
        address : IntPtr -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeProcessHandle<br />Handle to a process object that was previously passed to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtMapViewOfSection">NtMapViewOfSection(IntPtr, SafeProcessHandle, IntPtr, IntPtr, IntPtr, Int64, UIntPtr, SectionInherit, MemoryAllocationType, MemoryProtectionOptions)</a>.</dd><dt>address</dt><dd>Type: System.IntPtr<br />Pointer to the base virtual address of the view to unmap. 

 This value can be any virtual address within the view.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success, or the appropriate <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-Zwunmapviewofsection" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-Zwunmapviewofsection</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtUnmapViewOfSection">NtUnmapViewOfSection Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />