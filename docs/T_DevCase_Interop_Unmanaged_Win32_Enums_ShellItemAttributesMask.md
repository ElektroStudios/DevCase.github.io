# ShellItemAttributesMask Enumeration
 

Specifies the ttributes that can be retrieved on an item (file or folder) or set of items.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ShellItemAttributesMask
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ShellItemAttributesMask
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellItemAttributesMask
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ShellItemAttributesMask
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ShellItemAttributesMask
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.None">**None**</td><td>0</td><td /></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Browsable">**Browsable**</td><td>134217728</td><td>The specified items can be hosted inside a web browser or Windows Explorer frame.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.CanCopy">**CanCopy**</td><td>1</td><td>The specified items can be copied.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.CanDelete">**CanDelete**</td><td>32</td><td>The specified items can be deleted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.CanLink">**CanLink**</td><td>4</td><td>Shortcuts can be created for the specified items. This attribute has the same value as DROPEFFECT_LINK. 

 If a namespace extension returns this attribute, a Create Shortcut entry with a default handler is added to the shortcut menu that is displayed during drag-and-drop operations. 

 The extension can also implement its own handler for the link verb in place of the default. If the extension does so, it is responsible for creating the shortcut. 

 A Create Shortcut item is also added to the Windows Explorer File menu and to normal shortcut menus. 

 If the item is selected, your application's IContextMenu.InvokeCommand method is invoked with the lpVerb member of the CMINVOKECOMMANDINFO structure set to link. Your application is responsible for creating the link.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.CanMoniker">**CanMoniker**</td><td>4194304</td><td>Not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.CanMove">**CanMove**</td><td>2</td><td>The specified items can be moved.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.CanRename">**CanRename**</td><td>16</td><td>The specified items can be renamed. 

 Note that this value is essentially a suggestion; not all namespace clients allow items to be renamed. However, those that do must have this attribute set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.CapabilityMask">**CapabilityMask**</td><td>375</td><td>This flag is a mask for the capability attributes: CanCopy, CanMove, CanLink, CanRename, CanDelete, HasPropertySheet, and DropTarget. 

 Callers normally do not use this value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Compressed">**Compressed**</td><td>67108864</td><td>The specified items are compressed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.ContentsMask">**ContentsMask**</td><td>2147483648</td><td>This flag is a mask for content attributes, at present only HasSubfolder. 

 Callers normally do not use this value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.DisplayAttributeMask">**DisplayAttributeMask**</td><td>1032192</td><td>Do not use.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.DropTarget">**DropTarget**</td><td>256</td><td>The specified items are drop targets.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Encrypted">**Encrypted**</td><td>8192</td><td>The specified items are encrypted and might require special presentation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.FileSystemAncestor">**FileSystemAncestor**</td><td>268435456</td><td>The specified folders are either file system folders or contain at least one descendant (child, grandchild, or later) that is a file system (FileSystem) folder.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.FileSystem">**FileSystem**</td><td>1073741824</td><td>The specified folders or files are part of the file system (that is, they are files, directories, or root directories). 

 The parsed names of the items can be assumed to be valid Win32 file system paths. These paths can be either UNC or drive-letter based.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Folder">**Folder**</td><td>536870912</td><td>The specified items are folders. 

 Some items can be flagged with both Stream and Folder, such as a compressed file with a .zip file name extension. 

 Some applications might include this flag when testing for items that are both files and containers.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Ghosted">**Ghosted**</td><td>32768</td><td>The specified items are shown as dimmed and unavailable to the user.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.HasPropertySheet">**HasPropertySheet**</td><td>64</td><td>The specified items have property sheets.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.HasStorage">**HasStorage**</td><td>4194304</td><td>Not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.HasSubfolder">**HasSubfolder**</td><td>2147483648</td><td>The specified folders have subfolders. 

 The HasSubfolder attribute is only advisory and might be returned by Shell folder implementations even if they do not contain subfolders. Note, however, that the converse—failing to return HasSubfolder —definitively states that the folder objects do not have subfolders. 

 Returning HasSubfolder is recommended whenever a significant amount of time is required to determine whether any subfolders exist. For example, the Shell always returns HasSubfolder when a folder is located on a network drive.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Hidden">**Hidden**</td><td>524288</td><td>The item is hidden and should not be displayed unless the Show hidden files and folders option is enabled in Folder Settings.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.IsSlow">**IsSlow**</td><td>16384</td><td>Accessing the item (through IStream or other storage interfaces) is expected to be a slow operation. 

 Applications should avoid accessing items flagged with IsSlow. 

 Opening a stream for an item is generally a slow operation at all times. 

IsSlow indicates that it is expected to be especially slow, for example in the case of slow network connections or offline (FILE_ATTRIBUTE_OFFLINE) files. However, querying IsSlow is itself a slow operation. 

 Applications should query IsSlow only on a background thread. An alternate method, such as retrieving the PKEY_FileAttributes property and testing for FILE_ATTRIBUTE_OFFLINE, could be used in place of a method call that involves IsSlow.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Link">**Link**</td><td>65536</td><td>The specified items are shortcuts.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.NewContent">**NewContent**</td><td>2097152</td><td>The items contain new content, as defined by the particular application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.NonEnumerated">**NonEnumerated**</td><td>1048576</td><td>The items are nonenumerated items and should be hidden. 

 They are not returned through an enumerator such as that created by the IShellFolder.EnumObjects method.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.PropertyKeyShellItemAttributesMask">**PropertyKeyShellItemAttributesMask**</td><td>2164539392</td><td>Mask used by the PKEY_SFGAO flags property to determine attributes that are considered to cause slow calculations or lack context: 

IsSlow, ReadOnly, HasSubfolder, and Validate. 

 Callers normally do not use this value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.ReadOnly">**ReadOnly**</td><td>262144</td><td>The specified items are read-only. 

 In the case of folders, this means that new items cannot be created in those folders. 

 This should not be confused with the behavior specified by the FILE_ATTRIBUTE_READONLY flag retrieved by IColumnProvider.GetItemData in a SHCOLUMNDATA structure. FILE_ATTRIBUTE_READONLY has no meaning for Win32 file system folders.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Removable">**Removable**</td><td>33554432</td><td>The specified items are on removable media or are themselves removable devices.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Share">**Share**</td><td>131072</td><td>The specified objects are shared.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Storage">**Storage**</td><td>8</td><td>The specified items can be bound to an IStorage object through IShellFolder.BindToObject.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.StorageAncestor">**StorageAncestor**</td><td>8388608</td><td>Children of this item are accessible through IStream or IStorage. 

 Those children are flagged with Storage or Stream.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.StorageCapMask">**StorageCapMask**</td><td>1891958792</td><td>This flag is a mask for the storage capability attributes: Storage, Link, ReadOnly, Stream, StorageAncestor, FileSystemAncestor, Folder, and FileSystemAncestor. 

 Callers normally do not use this value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Stream">**Stream**</td><td>4194304</td><td>Indicates that the item has a stream associated with it. 

 That stream can be accessed through a call to IShellFolder.BindToObject or <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_BindToHandler">BindToHandler(IBindCtx, Guid, Guid)</a> with IID_IStream in the refIID parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.System">**System**</td><td>4096</td><td>The specified items are system items.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask.Validate">**Validate**</td><td>16777216</td><td>When specified as input, Validate instructs the folder to validate that the items contained in a folder or Shell item array exist. 

 If one or more of those items do not exist, IShellFolder.GetAttributesOf and IShellItemArray.GetAttributes return a failure code. This flag is never returned as an [out] value. 

 When used with the file system folder, Validate instructs the folder to discard cached properties retrieved by clients of IShellFolder2.GetDetailsEx that might have accumulated for the specified items.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/shell/sfgao" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/shell/sfgao</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />