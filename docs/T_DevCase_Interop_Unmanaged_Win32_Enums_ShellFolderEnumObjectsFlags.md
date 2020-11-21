# ShellFolderEnumObjectsFlags Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder_EnumObjects">EnumObjects(IntPtr, ShellFolderEnumObjectsFlags)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ShellFolderEnumObjectsFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ShellFolderEnumObjectsFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellFolderEnumObjectsFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ShellFolderEnumObjectsFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ShellFolderEnumObjectsFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.CheckingForChildern">**CheckingForChildern**</td><td>16</td><td>The calling application is checking for the existence of child items in the folder.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.Folders">**Folders**</td><td>32</td><td>Include items that are folders in the enumeration.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.NonFolders">**NonFolders**</td><td>64</td><td>Include items that are not folders in the enumeration.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.IncludeHidden">**IncludeHidden**</td><td>128</td><td>Include hidden items in the enumeration. This does not include hidden system items. (To include hidden system items, use IncludeSuperHidden.)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.InitOnFirstNext">**InitOnFirstNext**</td><td>256</td><td>No longer used; always assumed. 

<a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder_EnumObjects">EnumObjects(IntPtr, ShellFolderEnumObjectsFlags)</a> can return without validating the enumeration object. 

 Validation can be postponed until the first call to <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList_Next">Next(UInt32, IntPtr, UInt32)</a>. 

 Use this flag when a user interface might be displayed prior to the first <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList_Next">Next(UInt32, IntPtr, UInt32)</a> call. 

 For a user interface to be presented, hwnd must be set to a valid window handle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.NetPrinterSearch">**NetPrinterSearch**</td><td>512</td><td>The calling application is looking for printer objects.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.Shareable">**Shareable**</td><td>1024</td><td>The calling application is looking for resources that can be shared.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.Storage">**Storage**</td><td>2048</td><td>Include items with accessible storage and their ancestors, including hidden items.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.NavigationEnum">**NavigationEnum**</td><td>4096</td><td>Child folders should provide a navigation enumeration.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.FastItems">**FastItems**</td><td>8192</td><td>The calling application is looking for resources that can be enumerated quickly.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.FlatList">**FlatList**</td><td>16384</td><td>Enumerate items as a simple list even if the folder itself is not structured in that way.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.EnableAsync">**EnableAsync**</td><td>32768</td><td>The calling application is monitoring for change notifications. This means that the enumerator does not have to return all results. 

 Items can be reported through change notifications.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags.IncludeSuperHidden">**IncludeSuperHidden**</td><td>65536</td><td>Include hidden system items in the enumeration. This value does not include hidden non-system items. (To include hidden non-system items, use IncludeSuperHidden.)</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/ne-shobjidl_core-_shcontf" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/ne-shobjidl_core-_shcontf</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />