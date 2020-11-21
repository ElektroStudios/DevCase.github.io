# IShellLinkGetPathFlags Enumeration
 

IShellLink.GetPath method flags that specify the type of path information to retrieve.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum IShellLinkGetPathFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration IShellLinkGetPathFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkGetPathFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class IShellLinkGetPathFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type IShellLinkGetPathFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkGetPathFlags.ShortPath">**ShortPath**</td><td>1</td><td>Retrieves the standard short (8.3 format) file name.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkGetPathFlags.UncPriority">**UncPriority**</td><td>2</td><td>Retrieves the Universal Naming Convention (UNC) path name of the file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkGetPathFlags.RawPath">**RawPath**</td><td>4</td><td>Retrieves the raw path name. A raw path is something that might not exist and may include environment variables that need to be expanded.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb774944%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb774944%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />