# MiniDumpType Enumeration
 

Specifies the type of MiniDump information to be generated. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MiniDumpWriteDump">MiniDumpWriteDump(IntPtr, Int32, SafeHandle, MiniDumpType, MiniDumpExceptionInformation, IntPtr, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MiniDumpType
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MiniDumpType
```

**VB Usage**<br />
``` VB Usage
Dim instance As MiniDumpType
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MiniDumpType
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MiniDumpType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.Normal">**Normal**</td><td>0</td><td>Include just the information necessary to capture stack traces for all existing threads in a process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithDataSegs">**WithDataSegs**</td><td>1</td><td>Include the data sections from all loaded modules. 

 This results in the inclusion of global variables, which can make the minidump file significantly larger. 

 For per-module control, use the `MODULE_WRITE_FLAGS.ModuleWriteDataSeg` value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithFullMemory">**WithFullMemory**</td><td>2</td><td>Include all accessible memory in the process. 

 The raw memory data is included at the end, so that the initial structures can be mapped directly without the raw memory information. 

 This option can result in a very large file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithHandleData">**WithHandleData**</td><td>4</td><td>Include high-level information about the operating system handles that are active when the minidump is made.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.FilterMemory">**FilterMemory**</td><td>8</td><td>Stack and backing store memory written to the minidump file should be filtered to remove all but the pointer values necessary to reconstruct a stack trace.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.ScanMemory">**ScanMemory**</td><td>16</td><td>Stack and backing store memory should be scanned for pointer references to modules in the module list. 

 If a module is referenced by stack or backing store memory, the `MINIDUMP_CALLBACK_OUTPUT.ModuleWriteFlags` member is set to `MODULE_WRITE_FLAGS.ModuleReferencedByMemory`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithUnloadedModules">**WithUnloadedModules**</td><td>32</td><td>Include information from the list of modules that were recently unloaded, if this information is maintained by the operating system. 

 DbgHelp 5.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithIndirectlyReferencedMemory">**WithIndirectlyReferencedMemory**</td><td>64</td><td>Include pages with data referenced by locals or other stack memory. 

 This option can increase the size of the minidump file significantly. 

 DbgHelp 5.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.FilterModulePaths">**FilterModulePaths**</td><td>128</td><td>Filter module paths for information such as user names or important directories. 

 This option may prevent the system from locating the image file and should be used only in special situations. 

 DbgHelp 5.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithProcessThreadData">**WithProcessThreadData**</td><td>256</td><td>Include complete per-process and per-thread information from the operating system. 

 DbgHelp 5.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithPrivateReadWriteMemory">**WithPrivateReadWriteMemory**</td><td>512</td><td>Scan the virtual address space for <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">ReadWrite</a> memory to be included. 

 DbgHelp 5.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithoutOptionalData">**WithoutOptionalData**</td><td>1024</td><td>Reduce the data that is dumped by eliminating memory regions that are not essential to meet criteria specified for the dump. 

 This can avoid dumping memory that may contain data that is private to the user. However, it is not a guarantee that no private information will be present. 

 DbgHelp 6.1 and earlier: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithFullMemoryInfo">**WithFullMemoryInfo**</td><td>2048</td><td>Include memory region information. 

 DbgHelp 6.1 and earlier: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithThreadInfo">**WithThreadInfo**</td><td>4096</td><td>Include thread state information. 

 DbgHelp 6.1 and earlier: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithCodeSegs">**WithCodeSegs**</td><td>8192</td><td>Include all code and code-related sections from loaded modules to capture executable content. 

 For per-module control, use the `MODULE_WRITE_FLAGS.ModuleWriteCodeSegs` value. 

 DbgHelp 6.1 and earlier: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithoutAuxiliaryState">**WithoutAuxiliaryState**</td><td>16384</td><td>Turns off secondary auxiliary-supported memory gathering.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithFullAuxiliaryState">**WithFullAuxiliaryState**</td><td>32768</td><td>Requests that auxiliary data providers include their state in the dump image; the state data that is included is provider dependent. 

 This option can result in a large dump image.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.WithPrivateWriteCopyMemory">**WithPrivateWriteCopyMemory**</td><td>65536</td><td>Scans the virtual address space for <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">WriteCopy</a> memory to be included. 

 Prior to DbgHelp 6.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.IgnoreInaccessibleMemory">**IgnoreInaccessibleMemory**</td><td>131072</td><td>If you specify WithFullMemory, the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MiniDumpWriteDump">MiniDumpWriteDump(IntPtr, Int32, SafeHandle, MiniDumpType, MiniDumpExceptionInformation, IntPtr, IntPtr)</a> function will fail if the function cannot read the memory regions; however, if you include IgnoreInaccessibleMemory, the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MiniDumpWriteDump">MiniDumpWriteDump(IntPtr, Int32, SafeHandle, MiniDumpType, MiniDumpExceptionInformation, IntPtr, IntPtr)</a> function will ignore the memory read failures and continue to generate the dump. 

 Note that the inaccessible memory regions are not included in the dump. 

 Prior to DbgHelp 6.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.MiniDumpWithTokenInformation">**MiniDumpWithTokenInformation**</td><td>262144</td><td>Adds security token related data. 

 This will make the "!token" extension work when processing a user-mode dump. 

 Prior to DbgHelp 6.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.MiniDumpWithModuleHeaders">**MiniDumpWithModuleHeaders**</td><td>524288</td><td>Adds module header related data. 

 Prior to DbgHelp 6.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.MiniDumpFilterTriage">**MiniDumpFilterTriage**</td><td>1048576</td><td>Adds filter triage related data. 

 Prior to DbgHelp 6.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.MiniDumpWithAvxXStateContext">**MiniDumpWithAvxXStateContext**</td><td>2097152</td><td>

 Prior to DbgHelp 6.1: This value is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType.ValidTypeFlags">**ValidTypeFlags**</td><td>262143</td><td>Indicates which flags are valid.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/ms680519(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms680519(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />