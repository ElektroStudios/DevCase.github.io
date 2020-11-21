# SectionAttributes Enumeration
 

Specifies the attributes for a section object. 

 A section object represents a section of memory that can be shared. A process can use a section object to share parts of its memory address space (memory sections) with other processes. 

 Section objects also provide the mechanism by which a process can map a file into its memory address space. 

 Each memory section has one or more corresponding views. A view of a section is a part of the section that is actually visible to a process. The act of creating a view for a section is known as mapping a view of the section. 

 Each process that is manipulating the contents of a section has its own view; a process can also have multiple views (to the same or different sections).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SectionAttributes
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SectionAttributes
```

**VB Usage**<br />
``` VB Usage
Dim instance As SectionAttributes
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SectionAttributes
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SectionAttributes
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAttributes.Commit">**Commit**</td><td>134217728</td><td>If the file mapping object is backed by the operating system paging file, specifies that when a view of the file is mapped into a process address space, the entire range of pages is committed rather than reserved. 

 The system must have enough committable pages to hold the entire mapping. Otherwise, CreateFileMapping fails. 

 This attribute has no effect for file mapping objects that are backed by executable image files or data files. 

Commit cannot be combined with Reserve. 

 If no attribute is specified, Commit is assumed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAttributes.Image">**Image**</td><td>16777216</td><td>Specifies that the file that the hFile parameter specifies is an executable image file. 

 The Image attribute must be combined with a page protection value such as <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">ReadOnly</a>. However, this page protection value has no effect on views of the executable image file. Page protection for views of an executable image file is determined by the executable file itself. 

 No other attributes are valid with Image.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAttributes.ImageNoExecute">**ImageNoExecute**</td><td>285212672</td><td>Specifies that the file that the hFile parameter specifies is an executable image file that will not be executed and the loaded image file will have no forced integrity checks run. Additionally, mapping a view of a file mapping object created with the ImageNoExecute attribute will not invoke driver callbacks registered using the PsSetLoadImageNotifyRoutine kernel API. 

 The ImageNoExecute attribute must be combined with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">ReadOnly</a> page protection value. No other attributes are valid with ImageNoExecute.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAttributes.LargePages">**LargePages**</td><td>2147483648</td><td>Enables large pages to be used for file mapping objects that are backed by the operating system paging file. 

 This attribute is not supported for file mapping objects that are backed by executable image files or data files. 

 The maximum size of the file mapping object must be a multiple of the minimum size of a large page returned by the GetLargePageMinimum function. If it is not, CreateFileMappingFromApp fails. 

 When mapping a view of a file mapping object created with LargePages, the base address and view size must also be multiples of the minimum large page size. 

LargePages requires the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">LockMemoryPrivilege</a> privilege to be enabled in the caller's token. 

LargePages requires the Commit attribute to be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAttributes.NoCache">**NoCache**</td><td>268435456</td><td>Sets all pages to be non-cachable. 

 Applications should not use this attribute except when explicitly required for a device. Using the interlocked functions with memory that is mapped with NoCache can result in an EXCEPTION_ILLEGAL_INSTRUCTION exception. 

NoCache requires either the Reserve or Commit attribute to be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAttributes.Reserve">**Reserve**</td><td>67108864</td><td>If the file mapping object is backed by the operating system paging file, specifies that when a view of the file is mapped into a process address space, the entire range of pages is reserved for later use by the process rather than committed. 

 Reserved pages can be committed in subsequent calls to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function. After the pages are committed, they cannot be freed or decommitted with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualFree">VirtualFree(IntPtr, IntPtr, MemoryFreeType)</a> function. 

Reserve cannot be combined with Commit.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAttributes.WriteCombine">**WriteCombine**</td><td>1073741824</td><td>Sets all pages to be write-combined. 

 Applications should not use this attribute except when explicitly required for a device. Using the interlocked functions with memory that is mapped with WriteCombine can result in an EXCEPTION_ILLEGAL_INSTRUCTION exception. 

WriteCombine requires either the Reserve or Commit attribute to be set.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createfilemappinga" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createfilemappinga</a><a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />