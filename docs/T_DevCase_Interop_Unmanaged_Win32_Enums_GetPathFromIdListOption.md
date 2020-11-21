# GetPathFromIdListOption Enumeration
 

Determine the type of path returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetPathFromIDListEx">SHGetPathFromIDListEx(IntPtr, StringBuilder, UInt32, GetPathFromIdListOption)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum GetPathFromIdListOption
```

**VB**<br />
``` VB
Public Enumeration GetPathFromIdListOption
```

**VB Usage**<br />
``` VB Usage
Dim instance As GetPathFromIdListOption
```

**C++**<br />
``` C++
public enum class GetPathFromIdListOption
```

**F#**<br />
``` F#
type GetPathFromIdListOption
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetPathFromIdListOption.Default">**Default**</td><td>0</td><td>Win32 file names, servers, and root drives are included.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetPathFromIdListOption.AltName">**AltName**</td><td>1</td><td>Uses short file names.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetPathFromIdListOption.UNC">**UNC**</td><td>2</td><td>Include UNC printer names items.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shgetpathfromidlistex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shgetpathfromidlistex</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />