# IPropertyStore Interface
 

Exposes methods for enumerating, getting, and setting property values.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("886D8EEB-8CF2-4446-8D02-CDBA1DBDCF99")]
public interface IPropertyStore
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("886D8EEB-8CF2-4446-8D02-CDBA1DBDCF99")>
Public Interface IPropertyStore
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPropertyStore
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"886D8EEB-8CF2-4446-8D02-CDBA1DBDCF99")]
public interface class IPropertyStore
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("886D8EEB-8CF2-4446-8D02-CDBA1DBDCF99")>]
type IPropertyStore =  interface end
```

The IPropertyStore type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore_Commit">Commit</a></td><td>
Saves a property change.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore_GetAt">GetAt</a></td><td>
Gets a property key from an item's array of properties.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore_GetCount">GetCount</a></td><td>
Gets the number of properties attached to the file.</td></tr></table>&nbsp;
<a href="#ipropertystore-interface">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb761474(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb761474(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />