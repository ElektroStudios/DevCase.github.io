# CreateFileFlags Enumeration
 

Specifies the file or device flags for the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateFile">CreateFile(String, FileAccessRights, FileShare, IntPtr, FileMode, CreateFileFlags, IntPtr)</a> function. 

 These flags can be combined with any value of the FileAttributes enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum CreateFileFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration CreateFileFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As CreateFileFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class CreateFileFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type CreateFileFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.FileAttributeArchive">**FileAttributeArchive**</td><td>32</td><td>The file is a candidate for backup or removal.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.FileAttributeEncrypted">**FileAttributeEncrypted**</td><td>16384</td><td>The file or directory is encrypted. 

 For a file, this means that all data in the file is encrypted. 

 For a directory, this means that encryption is the default for newly created files and directories.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.FileAttributeHidden">**FileAttributeHidden**</td><td>2</td><td>The file is hidden, and thus is not included in an ordinary directory listing.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.FileAttributeNormal">**FileAttributeNormal**</td><td>128</td><td>The file is a standard file that has no special attributes. This attribute is valid only if it is used alone.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.FileAttributeOffline">**FileAttributeOffline**</td><td>4096</td><td>The file is offline. The data of the file is not immediately available.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.FileAttributeReadOnly">**FileAttributeReadOnly**</td><td>1</td><td>The file is read-only.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.FileAttributeSystem">**FileAttributeSystem**</td><td>4</td><td>The file is a system file. 

 That is, the file is part of the operating system or is used exclusively by the operating system.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.FileAttributeTemporary">**FileAttributeTemporary**</td><td>256</td><td>The file is temporary. A temporary file contains data that is needed while an application is executing but is not needed after the application is finished. 

 File systems try to keep all the data in memory for quicker access rather than flushing the data back to mass storage. 

 A temporary file should be deleted by the application As soon As it Is no longer needed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.BackupSemantics">**BackupSemantics**</td><td>33554432</td><td>The file is being opened or created for a backup or restore operation. 

 The system ensures that the calling process overrides file security checks when the process has <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">BackupPrivilege</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">RestorePrivilege</a> privileges. 

 You must set this flag to obtain a handle to a directory. A directory handle can be passed to some functions instead of a file handle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.DeleteOnClose">**DeleteOnClose**</td><td>67108864</td><td>The file is to be deleted immediately after all of its handles are closed, which includes the specified handle and any other open or duplicated handles. 

 If there are existing open handles to a file, the call fails unless they were all opened with the Delete share mode.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.NoBuffering">**NoBuffering**</td><td>536870912</td><td>he file or device is being opened with no system caching for data reads and writes. 

 This flag does not affect hard disk caching or memory mapped files. 

 There are strict requirements for successfully working with files opened with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateFile">CreateFile(String, FileAccessRights, FileShare, IntPtr, FileMode, CreateFileFlags, IntPtr)</a> using the NoBuffering flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.OpenNoRecall">**OpenNoRecall**</td><td>1048576</td><td>The file data is requested, but it should continue to be located in remote storage. It should not be transported back to local storage. 

 This flag is for use by remote storage systems.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.OpenReparsePoint">**OpenReparsePoint**</td><td>2097152</td><td>Normal reparse point processing will not occur; <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateFile">CreateFile(String, FileAccessRights, FileShare, IntPtr, FileMode, CreateFileFlags, IntPtr)</a> will attempt to open the reparse point. 

 When a file is opened, a file handle is returned, whether or not the filter that controls the reparse point is operational. 

 This flag cannot be used with the OpenOrCreate flag. 

 If the file is not a reparse point, then this flag is ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.Overlapped">**Overlapped**</td><td>1073741824</td><td>The file or device is being opened or created for asynchronous I/O. 

 When subsequent I/O operations are completed on this handle, the event specified in the `OVERLAPPED` structure will be set to the signaled state. 

 If this flag is specified, the file can be used for simultaneous read and write operations. 

 If this flag is not specified, then I/O operations are serialized, even if the calls to the read and write functions specify an `OVERLAPPED` structure.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.PosixSemantics">**PosixSemantics**</td><td>1048576</td><td>Access will occur according to POSIX rules. 

 This includes allowing multiple files with names, differing only in case, for file systems that support that naming. 

 Use care when using this option, because files created with this flag may not be accessible by applications that are written for MS-DOS or 16-bit Windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.RandomAccess">**RandomAccess**</td><td>268435456</td><td>Access is intended to be random. The system can use this as a hint to optimize file caching. 

 This flag has no effect if the file system does not support cached I/O and NoBuffering flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.SessionAware">**SessionAware**</td><td>8388608</td><td>The file or device is being opened with session awareness. 

 If this flag is not specified, then per-session devices (such as a device using RemoteFX USB Redirection) cannot be opened by processes running in session 0. 

 This flag has no effect for callers not in session 0. 

 This flag is supported only on server editions of Windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.SequentialScan">**SequentialScan**</td><td>134217728</td><td>Access is intended to be sequential from beginning to end. 

 The system can use this as a hint to optimize file caching. 

 This flag should not be used if read-behind (that is, reverse scans) will be used. 

 This flag has no effect if the file system does not support cached I/O and NoBuffering flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateFileFlags.WriteThrough">**WriteThrough**</td><td>2147483648</td><td>Write operations will not go through any intermediate cache, they will go directly to disk.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa363858%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa363858%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />