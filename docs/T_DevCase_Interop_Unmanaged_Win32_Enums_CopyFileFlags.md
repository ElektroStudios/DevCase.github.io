# CopyFileFlags Enumeration
 

Specifies options to use when copying a file with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CopyFileEx">CopyFileEx(String, String, Delegates.CopyProgressRoutine, IntPtr, Boolean, CopyFileFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum CopyFileFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration CopyFileFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As CopyFileFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class CopyFileFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type CopyFileFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileFlags.None">**None**</td><td>0</td><td /></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileFlags.FailIfExists">**FailIfExists**</td><td>1</td><td>The copy operation fails immediately if the target file already exists.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileFlags.NoBuffering">**NoBuffering**</td><td>4096</td><td>The copy operation is performed using unbuffered I/O, bypassing system I/O cache resources. 

 Recommended for very large file transfers. 

 ! This value is not supported in Windows XP and Windows Server 2003 !</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileFlags.Restartable">**Restartable**</td><td>2</td><td>Progress of the copy is tracked in the target file in case the copy fails. 

 The failed copy can be restarted at a later time by specifying the same values for `existingFileName` and `newFileName` parameters as those used in the call that failed. 

 This can significantly slow down the copy operation as the new file may be flushed multiple times during the copy operation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileFlags.OpenSourceForWrite">**OpenSourceForWrite**</td><td>4</td><td>The file is copied and the original file is opened for write access.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileFlags.AllowDecryptedDestination">**AllowDecryptedDestination**</td><td>8</td><td>An attempt to copy an encrypted file will succeed even if the destination copy cannot be encrypted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileFlags.CopySymbolicLink">**CopySymbolicLink**</td><td>2048</td><td>If the source file is a symbolic link, the destination file is also a symbolic link pointing to the same file that the source symbolic link is pointing to. 

 ! This value is not supported in Windows XP and Windows Server 2003 !</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/da-dk/library/windows/desktop/aa363852(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/da-dk/library/windows/desktop/aa363852(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />