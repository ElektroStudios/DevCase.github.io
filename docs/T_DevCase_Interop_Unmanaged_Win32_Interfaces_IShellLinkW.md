# IShellLinkW Interface
 

The `IShellLink` interface allows Shell links to be created, modified, or resolved.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("000214F9-0000-0000-C000-000000000046")]
public interface IShellLinkW
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("000214F9-0000-0000-C000-000000000046")>
Public Interface IShellLinkW
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"000214F9-0000-0000-C000-000000000046")]
public interface class IShellLinkW
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("000214F9-0000-0000-C000-000000000046")>]
type IShellLinkW =  interface end
```

The IShellLinkW type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_GetArguments">GetArguments</a></td><td>
Retrieves the command-line arguments associated with a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_GetDescription">GetDescription</a></td><td>
Retrieves the description string for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_GetHotkey">GetHotkey</a></td><td>
Retrieves the hot key for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_GetIconLocation">GetIconLocation</a></td><td>
Retrieves the location (path and index) of the icon for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_GetIDList">GetIDList</a></td><td>
Retrieves the list of item identifiers for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_GetPath">GetPath</a></td><td>
Retrieves the path and file name of a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_GetShowCmd">GetShowCmd</a></td><td>
Retrieves the ShowWindowFlags for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_GetWorkingDirectory">GetWorkingDirectory</a></td><td>
Retrieves the name of the working directory for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_Resolve">Resolve</a></td><td>
Attempts to find the target of a Shell link, even if it has been moved or renamed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_SetArguments">SetArguments</a></td><td>
Sets the command-line arguments for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_SetDescription">SetDescription</a></td><td>
Sets the description for a Shell link object. The description can be any application-defined string.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_SetHotkey">SetHotkey</a></td><td>
Sets a hot key for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_SetIconLocation">SetIconLocation</a></td><td>
Sets the location (path and index) of the icon for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_SetIDList">SetIDList</a></td><td>
Sets the pointer to an item identifier list (PIDL) for a Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_SetPath">SetPath</a></td><td>
Sets the path and file name of a Shell link object</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_SetRelativePath">SetRelativePath</a></td><td>
Sets the relative path to the Shell link object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_SetShowCmd">SetShowCmd</a></td><td>
Sets the show command for a Shell link object. 

 The show command sets the initial show state of the window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW_SetWorkingDirectory">SetWorkingDirectory</a></td><td>
Sets the name of the working directory for a Shell link object.</td></tr></table>&nbsp;
<a href="#ishelllinkw-interface">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/bb774950%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/bb774950%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />