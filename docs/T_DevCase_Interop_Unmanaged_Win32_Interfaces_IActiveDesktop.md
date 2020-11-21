# IActiveDesktop Interface
 

Allows a client program to manage the desktop items and wallpaper on a local computer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("F490EB00-1240-11D1-9888-006097DEACF9")]
public interface IActiveDesktop
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("F490EB00-1240-11D1-9888-006097DEACF9")>
Public Interface IActiveDesktop
```

**VB Usage**<br />
``` VB Usage
Dim instance As IActiveDesktop
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"F490EB00-1240-11D1-9888-006097DEACF9")]
public interface class IActiveDesktop
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("F490EB00-1240-11D1-9888-006097DEACF9")>]
type IActiveDesktop =  interface end
```

The IActiveDesktop type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop_ApplyChanges">ApplyChanges</a></td><td>
Applies changes to the Active Desktop and saves them in the registry.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop_GetDesktopItemCount">GetDesktopItemCount</a></td><td>
Gets a count of the desktop items.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop_GetPattern">GetPattern</a></td><td>
Gets the current pattern.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop_GetWallpaper">GetWallpaper</a></td><td>
Gets the current wallpaper.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop_SetPattern">SetPattern</a></td><td>
Sets the Active Desktop pattern.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop_SetWallpaper">SetWallpaper</a></td><td>
Sets the wallpaper for the Active Desktop.</td></tr></table>&nbsp;
<a href="#iactivedesktop-interface">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776357%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776357%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />