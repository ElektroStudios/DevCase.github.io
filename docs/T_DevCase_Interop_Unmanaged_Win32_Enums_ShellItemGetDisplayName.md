# ShellItemGetDisplayName Enumeration
 

Requests the form of an item's display name to retrieve through <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_GetDisplayName">GetDisplayName(ShellItemGetDisplayName)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetNameFromIDList">SHGetNameFromIDList(PIDL, ShellItemGetDisplayName, StringBuilder)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ShellItemGetDisplayName
```

**VB**<br />
``` VB
Public Enumeration ShellItemGetDisplayName
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellItemGetDisplayName
```

**C++**<br />
``` C++
public enum class ShellItemGetDisplayName
```

**F#**<br />
``` F#
type ShellItemGetDisplayName
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.DesktopAbsoluteEditing">**DesktopAbsoluteEditing**</td><td>2147794944</td><td>Returns the editing name relative to the desktop. In UI this name is suitable for display to the user.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.DesktopAbsoluteParsing">**DesktopAbsoluteParsing**</td><td>2147647488</td><td>Returns the parsing name relative to the desktop. This name is not suitable for use in UI.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.FileSystemPath">**FileSystemPath**</td><td>2147844096</td><td>Returns the item's file system path, if it has one. 

 Only items that report SFGAO_FILESYSTEM have a file system path. 

 When an item does not have a file system path, a call to IShellItem::GetDisplayName on that item will fail. 

 In UI this name is suitable for display to the user in some cases, but note that it might not be specified for all items.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.NormalDisplay">**NormalDisplay**</td><td>0</td><td>Returns the display name relative to the parent folder. In UI this name is generally ideal for display to the user.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.ParentRelative">**ParentRelative**</td><td>2148007937</td><td>Returns the path relative to the parent folder.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.ParentRelativeEditing">**ParentRelativeEditing**</td><td>2147684353</td><td>Returns the editing name relative to the parent folder. In UI this name is suitable for display to the user.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.ParentRelativeForAddressBar">**ParentRelativeForAddressBar**</td><td>2147991553</td><td>Returns the path relative to the parent folder in a friendly format as displayed in an address bar. 

 This name is suitable for display to the user.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.ParentRelativeForUI">**ParentRelativeForUI**</td><td>2148089857</td><td>Not documented. Introduced in Windows 8.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.ParentRelativeParsing">**ParentRelativeParsing**</td><td>2147581953</td><td>Returns the parsing name relative to the parent folder. This name is not suitable for use in UI.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName.Url">**Url**</td><td>2147909632</td><td>Returns the item's URL, if it has one. 

 Some items do not have a URL, and in those cases a call to IShellItem.GetDisplayName will fail. 

 This name is suitable for display to the user in some cases, but note that it might not be specified for all items.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/ne-shobjidl_core-_sigdn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/ne-shobjidl_core-_sigdn</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />