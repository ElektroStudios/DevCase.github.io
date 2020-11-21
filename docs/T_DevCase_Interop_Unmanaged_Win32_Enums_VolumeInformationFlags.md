# VolumeInformationFlags Enumeration
 

Specifies filesystem information flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetVolumeInformation">GetVolumeInformation(String, StringBuilder, Int32, UInt32, Int32, VolumeInformationFlags, StringBuilder, Int32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum VolumeInformationFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration VolumeInformationFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As VolumeInformationFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class VolumeInformationFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type VolumeInformationFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.CaseSensitiveSearch">**CaseSensitiveSearch**</td><td>1</td><td>The file system supports case-sensitive file names.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.CasePreservedNames">**CasePreservedNames**</td><td>2</td><td>The file system preserves the case of file names when it places a name on disk.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.UnicodeOnDisk">**UnicodeOnDisk**</td><td>4</td><td>The file system supports `Unicode` in file names as they appear on disk.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.PersistentACL">**PersistentACL**</td><td>8</td><td>The file system preserves and enforces `access control lists` (`ACL`).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.FileCompression">**FileCompression**</td><td>16</td><td>The file system supports file-based compression.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.VolumeQuotas">**VolumeQuotas**</td><td>32</td><td>The file system supports disk quotas.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.SparseFiles">**SparseFiles**</td><td>64</td><td>The file system supports sparse files.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.ReparsePoints">**ReparsePoints**</td><td>128</td><td>The file system supports re-parse points but does not index them, so `FindFirstVolumeMountPoint` and `FindNextVolumeMountPoint` functions will not work as expected.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.IsCompressed">**IsCompressed**</td><td>32768</td><td>The specified volume is a compressed volume, for example, a DoubleSpace volume.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.ObjectIDs">**ObjectIDs**</td><td>65536</td><td>The file system supports object identifiers.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.Encryption">**Encryption**</td><td>131072</td><td>The file system supports the `Encrypted File System` (`EFS`).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.NamedStreams">**NamedStreams**</td><td>262144</td><td>The file system supports named streams.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.IsReadOnlyVolume">**IsReadOnlyVolume**</td><td>524288</td><td>The specified volume is read-only.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.SequentialWriteOnce">**SequentialWriteOnce**</td><td>1048576</td><td>The volume supports a single sequential write.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.Transactions">**Transactions**</td><td>2097152</td><td>The volume supports transactions.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.HardLinks">**HardLinks**</td><td>4194304</td><td>The specified volume supports hard links.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.ExtendedFileAttributes">**ExtendedFileAttributes**</td><td>8388608</td><td>The specified volume supports extended attributes. 

 An extended attribute is a piece of application-specific metadata that an application can associate with a file and is not part of the file's data.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.OpenByFileId">**OpenByFileId**</td><td>16777216</td><td>The file system supports open by `FileID`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.UsnJournal">**UsnJournal**</td><td>33554432</td><td>The specified volume supports update sequence number (`USN`) journals.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags.DaxVolume">**DaxVolume**</td><td>536870912</td><td>The specified volume is a direct access (`DAX`) volume.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/aa364993%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/aa364993%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />