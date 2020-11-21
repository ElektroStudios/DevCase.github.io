# OpenFolderFlags Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHOpenFolderAndSelectItems">SHOpenFolderAndSelectItems(PIDL, UInt32, IntPtr[], OpenFolderFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum OpenFolderFlags
```

**VB**<br />
``` VB
Public Enumeration OpenFolderFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenFolderFlags
```

**C++**<br />
``` C++
public enum class OpenFolderFlags
```

**F#**<br />
``` F#
type OpenFolderFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenFolderFlags.None">**None**</td><td>0</td><td>No options.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenFolderFlags.Edit">**Edit**</td><td>1</td><td>Select an item and put its name in edit mode. 

 This flag can only be used when a single item is being selected. For multiple item selections, it is ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenFolderFlags.OpenDesktop">**OpenDesktop**</td><td>2</td><td>Select the item or items on the desktop rather than in a Windows Explorer window. 

 Note that if the desktop is obscured behind open windows, it will not be made visible.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shopenfolderandselectitems" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shopenfolderandselectitems</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />