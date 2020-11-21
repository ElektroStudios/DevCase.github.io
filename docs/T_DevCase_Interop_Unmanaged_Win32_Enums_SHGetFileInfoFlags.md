# SHGetFileInfoFlags Enumeration
 

Flags to use with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetFileInfo">SHGetFileInfo(IntPtr, FileAttributes, ShellFileInfo, UInt32, SHGetFileInfoFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SHGetFileInfoFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SHGetFileInfoFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SHGetFileInfoFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SHGetFileInfoFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SHGetFileInfoFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.Icon">**Icon**</td><td>256</td><td>Retrieve the handle to the icon that represents the file and the index of the icon within the system image list. 

 The handle is copied to the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_IconHandle">IconHandle</a> member of the structure specified by `refShellFileInfo` parameter, and the index is copied to the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_IconIndex">IconIndex</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.DisplayName">**DisplayName**</td><td>512</td><td>Retrieve the display name for the file, which is the name as it appears in Windows Explorer. 

 The name is copied to the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_DisplayName">DisplayName</a> member of the structure specified in `refShellFileInfo` parameter. 

 The returned display name uses the long file name, if there is one, rather than the 8.3 form of the file name. 

 Note that the display name can be affected by settings such as whether extensions are shown.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.TypeName">**TypeName**</td><td>1024</td><td>Retrieve the string that describes the file's type. 

 The string is copied to the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_TypeName">TypeName</a> member of the structure specified in `refShellFileInfo` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.Attributes">**Attributes**</td><td>2048</td><td>Retrieve the item attributes. 

 The attributes are copied to the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_Attributes">Attributes</a> member of the structure specified in the `refShellFileInfo` parameter. 

 These are the same attributes that are obtained from `IShellFolder::GetAttributesOf`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.IconLocation">**IconLocation**</td><td>4096</td><td>Retrieve the name of the file that contains the icon representing the file specified by `path` parameter, as returned by the `IExtractIcon::GetIconLocation` method of the file's icon handler. 

 Also retrieve the icon index within that file. 

 The name of the file containing the icon is copied to the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_DisplayName">DisplayName</a> member of the structure specified by `refShellFileInfo` parameter. 

 The icon's index is copied to that structure's <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_IconIndex">IconIndex</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.ExeType">**ExeType**</td><td>8192</td><td>Retrieve the type of the executable file if `path` parameter identifies an executable file. 

 The information is packed into the return value. 

 This flag cannot be specified with any other flags.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.SysIconIndex">**SysIconIndex**</td><td>16384</td><td>Retrieve the index of a system image list icon. 

 If successful, the index is copied to the iIcon member of `refShellFileInfo`. 

 The return value is a handle to the system image list. 

 Only those images whose indices are successfully copied to <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_IconIndex">IconIndex</a> are valid. 

 Attempting to access other images in the system image list will result in undefined behavior</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.LinkOverlay">**LinkOverlay**</td><td>32768</td><td>Modify Icon, causing the function to add the link overlay to the file's icon. 

 The Icon flag must also be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.Selected">**Selected**</td><td>65536</td><td>Modify Icon, causing the function to blend the file's icon with the system highlight color. 

 The Icon flag must also be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.AttributeSpecified">**AttributeSpecified**</td><td>131072</td><td>Modify Attributes to indicate that the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_Attributes">Attributes</a> member of the structure at `refShellFileInfo` parameter contains the specific attributes that are desired. 

 These attributes are passed to `IShellFolder::GetAttributesOf`. 

 If this flag is not specified, `0xFFFFFFFF` is passed to `IShellFolder::GetAttributesOf`, requesting all attributes. 

 This flag cannot be specified with the Icon flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.IconSizeLarge">**IconSizeLarge**</td><td>0</td><td>Modify Icon, causing the function to retrieve the file's large icon. 

 The image size is normally 32x32 pixels. However, if the Use large icons option is selected from the Effects section of the Appearance tab in Display Properties, the image is 48x48 pixels. 

 The Icon flag must also be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.IconSizeSmall">**IconSizeSmall**</td><td>1</td><td>Modify Icon, causing the function to retrieve the file's small icon. 

 Also used to modify SysIconIndex, causing the function to return the handle to the system image list that contains small icon images. 

 The image is the shell standard small icon size of 16x16, but the size can be customized by the user. 

 The Icon and/or SysIconIndex flag must also be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.IconSizeExtraLarge">**IconSizeExtraLarge**</td><td>2</td><td>Modify Icon, causing the function to retrieve the file's open icon. 

 Also used to modify SysIconIndex, causing the function to return the handle to the system image list that contains the file's small open icon. 

 A container object displays an open icon to indicate that the container is open. 

 The image is the Shell standard extra-large icon size. This is typically 48x48, but the size can be customized by the user. 

 The Icon and/or SysIconIndex flag must also be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.IconSizeJumbo">**IconSizeJumbo**</td><td>4</td><td>Modify Icon, causing the function to retrieve a Shell-sized icon. 

 If this flag is not specified the function sizes the icon according to the system metric values. 

 The image is normally 256x256 pixels. 

 The Icon flag must also be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.PIDL">**PIDL**</td><td>8</td><td>Indicate that `path` parameter is the address of an `ITEMIDLIST` structure rather than a path name.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.UseFileAttributes">**UseFileAttributes**</td><td>16</td><td>Indicates that the function should not attempt to access the file specified by `path` parameter. 

 Rather, it should act as if the file specified by `path` parameter exists with the file attributes passed in `fileAttributes` parameter. 

 This flag cannot be combined with the Attributes, ExeType, or PIDL flags.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.AddOverlays">**AddOverlays**</td><td>32</td><td>Apply the appropriate overlays to the file's icon. 

 The Icon flag must also be set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags.OverlayIndex">**OverlayIndex**</td><td>64</td><td>Return the index of the overlay icon. 

 The value of the overlay index is returned in the upper eight bits of the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_IconIndex">IconIndex</a> member of the structure specified by `refShellFileInfo` parameter. 

 This flag requires that the Icon be set as well.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/bb762179(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/bb762179(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />