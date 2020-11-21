# FileAccessRights Enumeration
 

Specifies file-specific access rights.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum FileAccessRights
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration FileAccessRights
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileAccessRights
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class FileAccessRights
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type FileAccessRights
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.ReadData">**ReadData**</td><td>1</td><td>For a file object, the right to read the corresponding file data. 

 For a directory object, the right to read the corresponding directory data.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.WriteData">**WriteData**</td><td>2</td><td>For a file object, the right to write data to the file. 

 For a directory object, the right to create a file in the directory (AddFile).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.AppendData">**AppendData**</td><td>4</td><td>For a file object, the right to append data to the file. 

 (For local files, write operations will not overwrite existing data if this flag is specified without WriteData.) 

 For a directory object, the right to create a subdirectory (AddSubdirectory).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.ReadExtendedAttributes">**ReadExtendedAttributes**</td><td>8</td><td>The right to read extended file attributes</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.WriteExtendedAttributes">**WriteExtendedAttributes**</td><td>16</td><td>The right to write extended file attributes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.Execute">**Execute**</td><td>32</td><td>For a native code file, the right to execute the file. 

 This access right given to scripts may cause the script to be executable, depending on the script interpreter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.DeleteChild">**DeleteChild**</td><td>64</td><td>For a directory, the right to delete a directory and all the files it contains, including read-only files.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.ReadAttributes">**ReadAttributes**</td><td>128</td><td>The right to read file attributes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.WriteAttributes">**WriteAttributes**</td><td>256</td><td>The right to write file attributes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.ListDirectory">**ListDirectory**</td><td>1</td><td>For a directory, the right to list the contents of the directory.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.AddFile">**AddFile**</td><td>2</td><td>For a directory, the right to create a file in the directory.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.AddSubdirectory">**AddSubdirectory**</td><td>4</td><td>For a directory, the right to create a subdirectory.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.Traverse">**Traverse**</td><td>32</td><td>For a directory, the right to traverse the directory. 

 By default, users are assigned the `BYPASS_TRAVERSE_CHECKING` privilege, which ignores the Traverse access right.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.CreatePipeInstance">**CreatePipeInstance**</td><td>4</td><td>

 For a named pipe, the right to create a pipe.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.StandardRightsRead">**StandardRightsRead**</td><td>131072</td><td>Same as <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">ReadControl</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights.StandardRightsWrite">**StandardRightsWrite**</td><td>131072</td><td>Same as <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsRead</a>.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/gg258116(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/gg258116(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />