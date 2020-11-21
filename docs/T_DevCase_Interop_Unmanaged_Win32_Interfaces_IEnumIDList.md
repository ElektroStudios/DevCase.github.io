# IEnumIDList Interface
 

Exposes a standard set of methods used to enumerate the pointers to item identifier lists (PIDLs) of the items in a Shell folder. 

 When a folder's <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder_EnumObjects">EnumObjects(IntPtr, ShellFolderEnumObjectsFlags)</a> method is called, it creates an enumeration object and passes a pointer to the object's IEnumIDList interface back to the calling application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("000214F2-0000-0000-C000-000000000046")]
public interface IEnumIDList
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("000214F2-0000-0000-C000-000000000046")>
Public Interface IEnumIDList
```

**VB Usage**<br />
``` VB Usage
Dim instance As IEnumIDList
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"000214F2-0000-0000-C000-000000000046")]
public interface class IEnumIDList
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("000214F2-0000-0000-C000-000000000046")>]
type IEnumIDList =  interface end
```

The IEnumIDList type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList_Clone">Clone</a></td><td>
Creates a new item enumeration object with the same contents and state as the current one.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList_Next">Next</a></td><td>
Retrieves the specified number of item identifiers in the enumeration sequence and advances the current position by the number of items retrieved.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList_Reset">Reset</a></td><td>
Returns to the beginning of the enumeration sequence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList_Skip">Skip</a></td><td>
Skips the specified number of elements in the enumeration sequence.</td></tr></table>&nbsp;
<a href="#ienumidlist-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ienumidlist" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ienumidlist</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />