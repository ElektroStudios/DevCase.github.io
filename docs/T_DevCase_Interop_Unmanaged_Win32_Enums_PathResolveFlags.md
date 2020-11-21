# PathResolveFlags Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathResolve">PathResolve(StringBuilder, String[], PathResolveFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum PathResolveFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration PathResolveFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As PathResolveFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class PathResolveFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type PathResolveFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathResolveFlags.VerifyExists">**VerifyExists**</td><td>1</td><td>Return `true` (`True` in Visual Basic) if the file's existence is verified; otherwise `false` (`False` in Visual Basic).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathResolveFlags.TryProgramExtensions">**TryProgramExtensions**</td><td>3</td><td>Look for the specified path with the following extensions appended: .pif, .com, .bat, .cmd, .lnk, and .exe.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathResolveFlags.FirstDirDefault">**FirstDirDefault**</td><td>4</td><td>Look first in the directory or directories specified by dirs.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathResolveFlags.DontFindLink">**DontFindLink**</td><td>8</td><td>Ignore .lnk files.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathResolveFlags.RequireAbsolute">**RequireAbsolute**</td><td>16</td><td>Require an absolute (full) path.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathresolve" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathresolve</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />