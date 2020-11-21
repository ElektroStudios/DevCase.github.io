# NativeMethods.NtCreateSection Method (IntPtr, UInt32, IntPtr, UInt64, MemoryProtectionOptions, SectionAttributes, SafeFileHandle)
 

Creates a section object. 

 A section object represents a section of memory that can be shared. A process can use a section object to share parts of its memory address space (memory sections) with other processes. 

 Section objects also provide the mechanism by which a process can map a file into its memory address space. 

 Each memory section has one or more corresponding views. A view of a section is a part of the section that is actually visible to a process. The act of creating a view for a section is known as mapping a view of the section. 

 Each process that is manipulating the contents of a section has its own view; a process can also have multiple views (to the same or different sections).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)]
public static NTStatus NtCreateSection(
	ref IntPtr refSection,
	uint desiredAccess,
	IntPtr objectAttributes,
	ref ulong refMaxSize,
	MemoryProtectionOptions pageProtection,
	SectionAttributes allocationAttributes,
	SafeFileHandle hFile
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", CallingConvention := CallingConvention.StdCall>]
Public Shared Function NtCreateSection ( 
	ByRef refSection As IntPtr,
	desiredAccess As UInteger,
	objectAttributes As IntPtr,
	ByRef refMaxSize As ULong,
	pageProtection As MemoryProtectionOptions,
	allocationAttributes As SectionAttributes,
	hFile As SafeFileHandle
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim refSection As IntPtr
Dim desiredAccess As UInteger
Dim objectAttributes As IntPtr
Dim refMaxSize As ULong
Dim pageProtection As MemoryProtectionOptions
Dim allocationAttributes As SectionAttributes
Dim hFile As SafeFileHandle
Dim returnValue As NTStatus

returnValue = NativeMethods.NtCreateSection(refSection, 
	desiredAccess, objectAttributes, 
	refMaxSize, pageProtection, allocationAttributes, 
	hFile)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", CallingConvention = CallingConvention::StdCall)]
static NTStatus NtCreateSection(
	IntPtr% refSection, 
	unsigned int desiredAccess, 
	IntPtr objectAttributes, 
	unsigned long long% refMaxSize, 
	MemoryProtectionOptions pageProtection, 
	SectionAttributes allocationAttributes, 
	SafeFileHandle^ hFile
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)>]
static member NtCreateSection : 
        refSection : IntPtr byref * 
        desiredAccess : uint32 * 
        objectAttributes : IntPtr * 
        refMaxSize : uint64 byref * 
        pageProtection : MemoryProtectionOptions * 
        allocationAttributes : SectionAttributes * 
        hFile : SafeFileHandle -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>refSection</dt><dd>Type: System.IntPtr<br />Pointer to a handle that receives a handle to the section object.</dd><dt>desiredAccess</dt><dd>Type: System.UInt32<br />Specifies the requested access to the section object.</dd><dt>objectAttributes</dt><dd>Type: System.IntPtr<br />Pointer to an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes</a> structure that specifies the object name and other attributes. 

 Use InitializeObjectAttributes to initialize this structure. 

 If the caller is not running in a system thread context, it must set the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ObjectHandleAttributes">KernelHandle</a> attribute when it calls InitializeObjectAttributes.</dd><dt>refMaxSize</dt><dd>Type: System.UInt64<br />Specifies the maximum size, in bytes, of the section. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtCreateSection">NtCreateSection(IntPtr, GenericAccessRights, ObjectAttributes, UInt64, MemoryProtectionOptions, SectionAttributes, SafeFileHandle)</a> rounds this value up to the nearest multiple of PAGE_SIZE. 

 If the section is backed by the paging file, *refMaxSize* specifies the actual size of the section. 

 If the section is backed by an ordinary file, *refMaxSize* specifies the maximum size that the file can be extended or mapped to.</dd><dt>pageProtection</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions</a><br />Specifies the protection to place on each page in the section. 

 Use one of the following four values: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">ReadOnly</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">ReadWrite</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">Execute</a>, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">WriteCopy</a>.</dd><dt>allocationAttributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SectionAttributes">DevCase.Interop.Unmanaged.Win32.Enums.SectionAttributes</a><br />Flags that determines the allocation attributes of the section.</dd><dt>hFile</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeFileHandle<br />Optionally specifies a handle for an open file object. 

 If the value of *hFile* is Zero, the section is backed by the paging file. Otherwise, the section is backed by the specified file.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success, or the appropriate <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-Zwcreatesection" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-Zwcreatesection</a><a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtCreateSection">NtCreateSection Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />