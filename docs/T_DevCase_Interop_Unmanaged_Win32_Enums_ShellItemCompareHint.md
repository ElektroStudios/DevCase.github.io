# ShellItemCompareHint Enumeration
 

Used to determine how to compare two Shell items. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_Compare">Compare(IShellItem, ShellItemCompareHint)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ShellItemCompareHint
```

**VB**<br />
``` VB
Public Enumeration ShellItemCompareHint
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellItemCompareHint
```

**C++**<br />
``` C++
public enum class ShellItemCompareHint
```

**F#**<br />
``` F#
type ShellItemCompareHint
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemCompareHint.AllFields">**AllFields**</td><td>2147483648</td><td>Exact comparison of two instances of a Shell item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemCompareHint.Canonical">**Canonical**</td><td>268435456</td><td>This relates to the iOrder parameter of the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_Compare">Compare(IShellItem, ShellItemCompareHint)</a> interface and indicates that the comparison is based on a canonical name.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemCompareHint.Display">**Display**</td><td>0</td><td>This relates to the iOrder parameter of the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_Compare">Compare(IShellItem, ShellItemCompareHint)</a> interface and indicates that the comparison is based on the display in a folder view.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemCompareHint.TestFileSysPathIfNotEqual">**TestFileSysPathIfNotEqual**</td><td>536870912</td><td>If the Shell items are not the same, test the file system paths.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ishellitem-compare" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ishellitem-compare</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />