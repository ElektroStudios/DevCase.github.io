# NativeMethods.NtMapViewOfSection Method (IntPtr, IntPtr, IntPtr, IntPtr, IntPtr, Int64, UIntPtr, SectionInherit, MemoryAllocationType, MemoryProtectionOptions)
 

Maps a view of a section into the virtual address space of a subject process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)]
public static NTStatus NtMapViewOfSection(
	IntPtr hSection,
	IntPtr hProcess,
	ref IntPtr refBaseAddress,
	IntPtr zeroBits,
	IntPtr commitSize,
	[OptionalAttribute] ref long refSectionOffset,
	ref UIntPtr refViewSize,
	SectionInherit sectionInherit,
	MemoryAllocationType allocationType,
	MemoryProtectionOptions protection
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", CallingConvention := CallingConvention.StdCall>]
Public Shared Function NtMapViewOfSection ( 
	hSection As IntPtr,
	hProcess As IntPtr,
	ByRef refBaseAddress As IntPtr,
	zeroBits As IntPtr,
	commitSize As IntPtr,
	<OptionalAttribute> ByRef refSectionOffset As Long,
	ByRef refViewSize As UIntPtr,
	sectionInherit As SectionInherit,
	allocationType As MemoryAllocationType,
	protection As MemoryProtectionOptions
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim hSection As IntPtr
Dim hProcess As IntPtr
Dim refBaseAddress As IntPtr
Dim zeroBits As IntPtr
Dim commitSize As IntPtr
Dim refSectionOffset As Long
Dim refViewSize As UIntPtr
Dim sectionInherit As SectionInherit
Dim allocationType As MemoryAllocationType
Dim protection As MemoryProtectionOptions
Dim returnValue As NTStatus

returnValue = NativeMethods.NtMapViewOfSection(hSection, 
	hProcess, refBaseAddress, zeroBits, 
	commitSize, refSectionOffset, refViewSize, 
	sectionInherit, allocationType, 
	protection)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", CallingConvention = CallingConvention::StdCall)]
static NTStatus NtMapViewOfSection(
	[InAttribute] IntPtr hSection, 
	[InAttribute] IntPtr hProcess, 
	IntPtr% refBaseAddress, 
	[InAttribute] IntPtr zeroBits, 
	[InAttribute] IntPtr commitSize, 
	[OptionalAttribute] long long% refSectionOffset, 
	UIntPtr% refViewSize, 
	[InAttribute] SectionInherit sectionInherit, 
	[InAttribute] MemoryAllocationType allocationType, 
	[InAttribute] MemoryProtectionOptions protection
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)>]
static member NtMapViewOfSection : 
        hSection : IntPtr * 
        hProcess : IntPtr * 
        refBaseAddress : IntPtr byref * 
        zeroBits : IntPtr * 
        commitSize : IntPtr * 
        [<OptionalAttribute>] refSectionOffset : int64 byref * 
        refViewSize : UIntPtr byref * 
        sectionInherit : SectionInherit * 
        allocationType : MemoryAllocationType * 
        protection : MemoryProtectionOptions -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>hSection</dt><dd>Type: System.IntPtr<br />Handle to a section object. 

 This handle is created by a successful call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtCreateSection">NtCreateSection(IntPtr, GenericAccessRights, ObjectAttributes, UInt64, MemoryProtectionOptions, SectionAttributes, SafeFileHandle)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtOpenSection">NtOpenSection(IntPtr, GenericAccessRights, IntPtr)</a>.</dd><dt>hProcess</dt><dd>Type: System.IntPtr<br />Handle to the object that represents the process that the view should be mapped into. 

 The handle must have been opened with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a> access.</dd><dt>refBaseAddress</dt><dd>Type: System.IntPtr<br />Pointer to a variable that receives the base address of the view. 

 If the value of this parameter is not Zero, the view is allocated starting at the specified virtual address rounded down to the next 64-kilobyte address boundary.</dd><dt>zeroBits</dt><dd>Type: System.IntPtr<br />Specifies the number of high-order address bits that must be zero in the base address of the section view. 

 The value of this parameter must be less than 21 and is used only if *refBaseAddress* is NULL—in other words, when the caller allows the system to determine where to allocate the view.</dd><dt>commitSize</dt><dd>Type: System.IntPtr<br />Specifies the size, in bytes, of the initially committed region of the view. 

*commitSize* is meaningful only for page-file backed sections and is rounded up to the nearest multiple of PAGE_SIZE. 

 (for sections that map files, both the data and the image are committed at section-creation time).</dd><dt>refSectionOffset (Optional)</dt><dd>Type: System.Int64<br />A pointer to a variable that receives the offset, in bytes, from the beginning of the section to the view. 

 If this pointer is not Zero, the offset is rounded down to the next allocation-granularity size boundary.</dd><dt>refViewSize</dt><dd>Type: System.UIntPtr<br />A pointer to a SIZE_T variable. 

 If the initial value of this variable is zero, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtMapViewOfSection">NtMapViewOfSection(IntPtr, SafeProcessHandle, IntPtr, IntPtr, IntPtr, Int64, UIntPtr, SectionInherit, MemoryAllocationType, MemoryProtectionOptions)</a> maps a view of the section that starts at *refSectionOffset* and continues to the end of the section. Otherwise, the initial value specifies the view's size, in bytes. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtMapViewOfSection">NtMapViewOfSection(IntPtr, SafeProcessHandle, IntPtr, IntPtr, IntPtr, Int64, UIntPtr, SectionInherit, MemoryAllocationType, MemoryProtectionOptions)</a> always rounds this value up to the nearest multiple of PAGE_SIZE before mapping the view. 

 On return, the value receives the actual size, in bytes, of the view.</dd><dt>sectionInherit</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SectionInherit">DevCase.Interop.Unmanaged.Win32.Enums.SectionInherit</a><br />Specifies how the view is to be shared with child processes.</dd><dt>allocationType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType</a><br />Specifies a set of flags that describes the type of allocation to be performed for the specified region of pages. 

 The valid flags are <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">LargePages</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">Reserve</a>, and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">TopDown</a>. 

 Although <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">Commit</a> is not allowed, it is implied unless <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">Reserve</a> is specified.</dd><dt>protection</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions</a><br />Specifies the type of protection for the region of initially committed pages. 

 Device and intermediate drivers should set this value to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">ReadWrite</a>.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success, or the appropriate <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-Zwmapviewofsection" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-Zwmapviewofsection</a><a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtMapViewOfSection">NtMapViewOfSection Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />