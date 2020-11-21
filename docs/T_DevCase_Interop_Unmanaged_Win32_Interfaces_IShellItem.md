# IShellItem Interface
 

Exposes a method to return either icons or thumbnails for Shell items. 

 If no thumbnail or icon is available for the requested item, a per-class icon may be provided from the Shell

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("43826d1e-e718-42ee-bc55-a1e261c37bfe")]
public interface IShellItem
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("43826d1e-e718-42ee-bc55-a1e261c37bfe")>
Public Interface IShellItem
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellItem
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"43826d1e-e718-42ee-bc55-a1e261c37bfe")]
public interface class IShellItem
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("43826d1e-e718-42ee-bc55-a1e261c37bfe")>]
type IShellItem =  interface end
```

The IShellItem type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_BindToHandler">BindToHandler</a></td><td>
Binds to a handler for an item as specified by the handler ID value (BHID).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_Compare">Compare</a></td><td>
Compares two IShellItem objects.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_GetAttributes">GetAttributes</a></td><td>
Gets a requested set of attributes of the IShellItem object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_GetDisplayName">GetDisplayName</a></td><td>
Gets the display name of the IShellItem object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem_GetParent">GetParent</a></td><td>
Gets the parent of an IShellItem object.</td></tr></table>&nbsp;
<a href="#ishellitem-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/shobjidl_core/nn-shobjidl_core-ishellitem" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/shobjidl_core/nn-shobjidl_core-ishellitem</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />