# MemoryProtectionOptions Enumeration
 

Specifies memory-protection options. 

 You must specify one of the following values when allocating or protecting a page in memory. 

 Protection attributes cannot be assigned to a portion of a page; they can only be assigned to a whole page

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MemoryProtectionOptions
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MemoryProtectionOptions
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryProtectionOptions
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MemoryProtectionOptions
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MemoryProtectionOptions
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.Execute">**Execute**</td><td>16</td><td>Enables execute access to the committed region of pages. 

 An attempt to write to the committed region results in an access violation. 

 This flag is not supported by the `CreateFileMapping` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.ExecuteRead">**ExecuteRead**</td><td>32</td><td>Enables execute or read-only access to the committed region of pages. 

 An attempt to write to the committed region results in an access violation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.ExecuteReadWrite">**ExecuteReadWrite**</td><td>64</td><td>Enables execute, read-only, or read/write access to the committed region of pages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.ExecuteWriteCopy">**ExecuteWriteCopy**</td><td>128</td><td>Enables execute, read-only, or copy-on-write access to a mapped view of a file mapping object. 

 An attempt to write to a committed copy-on-write page results in a private copy of the page being made for the process. 

 The private page is marked as ExecuteReadWrite, and the change is written to the new page. 

 This flag is not supported by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> functions.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.NoAccess">**NoAccess**</td><td>1</td><td>Disables all access to the committed region of pages. 

 An attempt to read from, write to, or execute the committed region results in an access violation. 

 This flag is not supported by the `CreateFileMapping` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.ReadOnly">**ReadOnly**</td><td>2</td><td>Enables read-only access to the committed region of pages. 

 An attempt to write to the committed region results in an access violation. 

 If `Data Execution Prevention` feature is enabled in the current Windows operating system, an attempt to execute code in the committed region results in an access violation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.ReadWrite">**ReadWrite**</td><td>4</td><td>Enables read-only or read/write access to the committed region of pages. 

 If `Data Execution Prevention` feature is enabled in the current Windows operating system, attempting to execute code in the committed region results in an access violation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.WriteCopy">**WriteCopy**</td><td>8</td><td>Enables read-only or copy-on-write access to a mapped view of a file mapping object. 

 An attempt to write to a committed copy-on-write page results in a private copy of the page being made for the process. 

 The private page is marked as ReadWrite, and the change is written to the new page. 

 If `Data Execution Prevention` feature is enabled in the current Windows operating system, attempting to execute code in the committed region results in an access violation. 

 This flag is not supported by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> functions.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.Guard">**Guard**</td><td>256</td><td>Pages in the region become guard pages. 

 Any attempt to access a guard page causes the system to raise a `STATUS_GUARD_PAGE_VIOLATION` exception and turn off the guard page status. 

 Guard pages thus act as a one-time access alarm. 

 When an access attempt leads the system to turn off guard page status, the underlying page protection takes over. 

 If a guard page exception occurs during a system service, the service typically returns a failure status indicator. 

 This value cannot be used with NoAccess. 

 This flag is not supported by the `CreateFileMapping` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.NoCache">**NoCache**</td><td>512</td><td>Sets all pages to be non-cachable. 

 Applications should not use this attribute except when explicitly required for a device. 

 Using the interlocked functions with memory that is mapped with `SEC_NOCACHE` can result in an `EXCEPTION_ILLEGAL_INSTRUCTION` exception. 

 The NoCache flag cannot be used with the Guard, NoAccess, or WriteCombine flags. 

 The NoCache flag can be used only when allocating private memory with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a>, or `VirtualAllocExNuma` functions. 

 To enable non-cached memory access for shared memory, specify the `SEC_NOCACHE` flag when calling the `CreateFileMapping` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions.WriteCombine">**WriteCombine**</td><td>1024</td><td>Sets all pages to be write-combined. 

 Applications should not use this attribute except when explicitly required for a device. 

 Using the interlocked functions with memory that is mapped as write-combined can result in an `EXCEPTION_ILLEGAL_INSTRUCTION` exception. 

 The PAGE_WRITECOMBINE flag cannot be specified with the PAGE_NOACCESS, PAGE_GUARD, and PAGE_NOCACHE flags. 

 The WriteCombine flag can be used only when allocating private memory with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a>, or `VirtualAllocExNuma` functions. 

 To enable write-combined memory access for shared memory, specify the `SEC_WRITECOMBINE` flag when calling the `CreateFileMapping` function.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366786%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366786%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />