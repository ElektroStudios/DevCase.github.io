# IShellItemImageFactory Interface
 

Exposes a method to return either icons or thumbnails for Shell items. 

 If no thumbnail or icon is available for the requested item, a per-class icon may be provided from the Shell

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[GuidAttribute("bcc18b79-ba16-442f-80c4-8a59c30c463b")]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
public interface IShellItemImageFactory
```

**VB**<br />
``` VB
<ComImportAttribute>
<GuidAttribute("bcc18b79-ba16-442f-80c4-8a59c30c463b")>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
Public Interface IShellItemImageFactory
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellItemImageFactory
```

**C++**<br />
``` C++
[ComImportAttribute]
[GuidAttribute(L"bcc18b79-ba16-442f-80c4-8a59c30c463b")]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
public interface class IShellItemImageFactory
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<GuidAttribute("bcc18b79-ba16-442f-80c4-8a59c30c463b")>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
type IShellItemImageFactory =  interface end
```

The IShellItemImageFactory type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItemImageFactory_GetImage">GetImage</a></td><td>
Gets an HBITMAP that represents an IShellItem. The default behavior is to load a thumbnail. If there is no thumbnail for the current IShellItem, it retrieves an HBITMAP for the icon of the item. The thumbnail or icon is extracted if it is not currently cached.</td></tr></table>&nbsp;
<a href="#ishellitemimagefactory-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ishellitemimagefactory" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ishellitemimagefactory</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />