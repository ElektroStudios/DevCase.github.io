# IOpenControlPanel Interface
 

Exposes methods that retrieve the view state of the Control Panel, the path of individual Control Panel items, and that open either the Control Panel itself or an individual Control Panel item.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("D11AD862-66DE-4DF4-BF6C-1F5621996AF1")]
public interface IOpenControlPanel
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("D11AD862-66DE-4DF4-BF6C-1F5621996AF1")>
Public Interface IOpenControlPanel
```

**VB Usage**<br />
``` VB Usage
Dim instance As IOpenControlPanel
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"D11AD862-66DE-4DF4-BF6C-1F5621996AF1")]
public interface class IOpenControlPanel
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("D11AD862-66DE-4DF4-BF6C-1F5621996AF1")>]
type IOpenControlPanel =  interface end
```

The IOpenControlPanel type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IOpenControlPanel_GetCurrentView">GetCurrentView</a></td><td>
Gets the most recent Control Panel view.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IOpenControlPanel_GetPath">GetPath</a></td><td>
Gets the path of a specified Control Panel item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IOpenControlPanel_Open">Open</a></td><td>
Opens the specified Control Panel item, optionally to a specific page.</td></tr></table>&nbsp;
<a href="#iopencontrolpanel-interface">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb775392%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb775392%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />