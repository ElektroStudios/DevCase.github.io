# ShellFoldermGetDisplayName Enumeration
 

Defines the values used with the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder_GetDisplayNameOf">GetDisplayNameOf(PIDL, ShellFoldermGetDisplayName)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder_SetNameOf">SetNameOf(IntPtr, PIDL, String, ShellFoldermGetDisplayName, PIDL)</a> methods to specify the type of file or folder names used by those methods.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ShellFoldermGetDisplayName
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ShellFoldermGetDisplayName
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellFoldermGetDisplayName
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ShellFoldermGetDisplayName
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ShellFoldermGetDisplayName
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFoldermGetDisplayName.ForaddressBar">**ForaddressBar**</td><td>16384</td><td>The name is displayed in an address bar combo box.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFoldermGetDisplayName.ForEditing">**ForEditing**</td><td>4096</td><td>The name is used for in-place editing when the user renames the item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFoldermGetDisplayName.ForParsing">**ForParsing**</td><td>32768</td><td>The name is used for parsing. That is, it can be passed to <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder_ParseDisplayName">ParseDisplayName(IntPtr, IBindCtx, String, UInt32, PIDL, ShellItemAttributesMask)</a> to recover the object's PIDL. 

 The form this name takes depends on the particular object. 

 When ForParsing is used alone, the name is relative to the desktop. 

 When combined with InFolder, the name is relative to the folder from which the request was made.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFoldermGetDisplayName.InFolder">**InFolder**</td><td>1</td><td>The name is relative to the folder from which the request was made. This is the name display to the user when used in the context of the folder. For example, it is used in the view and in the address bar path segment for the folder. 

 This name should not include disambiguation information— for instance "username" instead of "username (on Machine)" for a particular user's folder. 

 Use this flag in combinations with ForParsing and ForEditing.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellFoldermGetDisplayName.Normal">**Normal**</td><td>0</td><td>When not combined with another flag, return the parent-relative name that identifies the item, suitable for displaying to the user. 

 This name often does not include extra information such as the file name extension and does not need to be unique. 

 This name might include information that identifies the folder that contains the item. For instance, this flag could cause <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder_GetDisplayNameOf">GetDisplayNameOf(PIDL, ShellFoldermGetDisplayName)</a> to return the string "username (on Machine)" for a particular user's folder.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/ne-shobjidl_core-_shgdnf" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/ne-shobjidl_core-_shgdnf</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />