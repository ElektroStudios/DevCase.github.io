# AppbarMessages Enumeration
 

Specifies an edge of the screen. 

 For <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData_Edge">Edge</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum AppbarMessages
```

**VB**<br />
``` VB
Public Enumeration AppbarMessages
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppbarMessages
```

**C++**<br />
``` C++
public enum class AppbarMessages
```

**F#**<br />
``` F#
type AppbarMessages
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.New">**New**</td><td>0</td><td>Registers a new appbar and specifies the message identifier that the system should use to send notification messages to the `appbar`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.Remove">**Remove**</td><td>1</td><td>Unregisters an `appbar`, removing the bar from the system's internal list.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.QueryPos">**QueryPos**</td><td>2</td><td>Requests a size and screen position for an `appbar`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.SetPos">**SetPos**</td><td>3</td><td>Sets the size and screen position of an `appbar`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.GetState">**GetState**</td><td>4</td><td>Retrieves the autohide and always-on-top states of the Windows taskbar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.GetTaskbarPos">**GetTaskbarPos**</td><td>5</td><td>Retrieves the bounding rectangle of the Windows taskbar. 

 Note that this applies only to the system taskbar 

 Other objects, particularly toolbars supplied with third-party software, also can be present. 

 As a result, some of the screen area not covered by the Windows taskbar might not be visible to the user. 

 To retrieve the area of the screen not covered by both the taskbar and other app bars, the working area available to your application, use the `GetMonitorInfo` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.Activate">**Activate**</td><td>6</td><td>Notifies the system to activate or deactivate an `appbar`. The `lParam` member of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData">AppbarData</a> pointed to by `pData` is set to `true` (`True` in Visual Basic) to activate or `false` (`False` in Visual Basic) to deactivate.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.GetAutoHideBar">**GetAutoHideBar**</td><td>7</td><td>Retrieves the handle to the autohide `appbar` associated with a particular edge of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.SetAutoHideBar">**SetAutoHideBar**</td><td>8</td><td>Registers or unregisters an autohide `appbar` for an edge of the screen.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.WindowPosChanged">**WindowPosChanged**</td><td>9</td><td>Notifies the system when an appbar's position has changed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages.SetState">**SetState**</td><td>10</td><td>Windows XP and later: Sets the state of the `appbar`'s autohide and always-on-top attributes.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762108(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762108(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />