# DirectoryManagementControlCodes Enumeration
 

Specifies Directory Management Control Codes to use with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeviceIoControl">DeviceIoControl(IntPtr, DirectoryManagementControlCodes, IntPtr, Int32, IntPtr, Int32, Int32, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum DirectoryManagementControlCodes
```

**VB**<br />
``` VB
Public Enumeration DirectoryManagementControlCodes
```

**VB Usage**<br />
``` VB Usage
Dim instance As DirectoryManagementControlCodes
```

**C++**<br />
``` C++
public enum class DirectoryManagementControlCodes
```

**F#**<br />
``` F#
type DirectoryManagementControlCodes
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DirectoryManagementControlCodes.GetCompression">**GetCompression**</td><td>589884</td><td>Retrieves the current compression state of a file or directory on a volume whose file system supports per-stream compression.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DirectoryManagementControlCodes.SetCompression">**SetCompression**</td><td>589888</td><td>Retrieves the current compression state of a file or directory on a volume whose file system supports per-stream compression.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DirectoryManagementControlCodes.SetReparsePoint">**SetReparsePoint**</td><td>589988</td><td>Sets a reparse point on a file or directory.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DirectoryManagementControlCodes.GetReparsePoint">**GetReparsePoint**</td><td>589992</td><td>Retrieves the reparse point data associated with the file or directory identified by the specified handle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DirectoryManagementControlCodes.DeleteReparsePoint">**DeleteReparsePoint**</td><td>589996</td><td>Deletes a reparse point from the specified file or directory.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa363948(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa363948(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />