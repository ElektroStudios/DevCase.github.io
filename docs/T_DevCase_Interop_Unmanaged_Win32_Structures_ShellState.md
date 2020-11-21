# ShellState Structure
 

Contains settings for the Shell's state. 

 This structure is used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetSetSettings">SHGetSetSettings(ShellState, ShellStateFlags, Boolean)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct ShellState
```

**VB**<br />
``` VB
Public Structure ShellState
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellState
```

**C++**<br />
``` C++
public value class ShellState
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ShellState =  struct end
```

The ShellState type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_AutoCheckboxSelection">AutoCheckboxSelection</a></td><td>
Windows VISTA and above only. 

`true` (`True` in Visual Basic) to use the Windows Vista-style checkbox folder views, `false` (`False` in Visual Basic) to use the classic views.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_DesktopHtml">DesktopHtml</a></td><td>
`true` (`True` in Visual Basic) to use Active Desktop, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_DontPrettyPath">DontPrettyPath</a></td><td>
`true` (`True` in Visual Basic) to prevent the conversion of the path to all lowercase characters.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_DoubleClickInWebView">DoubleClickInWebView</a></td><td>
`true` (`True` in Visual Basic) to require a double-click to open an item when in web view.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ExplorerSeparateProcess">ExplorerSeparateProcess</a></td><td>
`true` (`True` in Visual Basic) to launch folder windows in separate processes, `false` (`False` in Visual Basic) to launch in the same process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_HideDesktopIcons">HideDesktopIcons</a></td><td>
`true` (`True` in Visual Basic) to hide desktop icons, `false` (`False` in Visual Basic) to show them.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_MapNetDrvBtn">MapNetDrvBtn</a></td><td>
`true` (`True` in Visual Basic) to display a Map Network Drive button.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_NoConfirmRecycle">NoConfirmRecycle</a></td><td>
`true` (`True` in Visual Basic) to show no confirmation dialog box when deleting items to the Recycle Bin, 

`false` (`False` in Visual Basic) to display the confirmation dialog box.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_NoNetCrawling">NoNetCrawling</a></td><td>
`true` (`True` in Visual Basic) to disable automatic searching for network folders and printers.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowAllObjects">ShowAllObjects</a></td><td>
`true` (`True` in Visual Basic) to show all objects, including hidden files And folders. 

`false` (`False` in Visual Basic) to hide hidden files And folders.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowCompressedFilesColor">ShowCompressedFilesColor</a></td><td>
`true` (`True` in Visual Basic) to show encrypted or compressed NTFS files in color.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowFilenameExtensions">ShowFilenameExtensions</a></td><td>
`true` (`True` in Visual Basic) to show file name extensions, `false` (`False` in Visual Basic) to hide them.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowIconsOnly">ShowIconsOnly</a></td><td>
Windows VISTA and above only. 

`true` (`True` in Visual Basic) to show generic icons only, `false` (`False` in Visual Basic) to show thumbnail-style icons in folders.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowInfoTip">ShowInfoTip</a></td><td>
`true` (`True` in Visual Basic) to show a pop-up description for folders and files.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowStatusBar">ShowStatusBar</a></td><td>
Windows 8 and above only. 

`true` (`True` in Visual Basic) to show the status bar; otherwise, FALSE.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowSuperHiddenFiles">ShowSuperHiddenFiles</a></td><td>
`true` (`True` in Visual Basic) to show operating system files.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowSystemFiles">ShowSystemFiles</a></td><td>
`true` (`True` in Visual Basic) to show system files, `false` (`False` in Visual Basic) to hide them.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowTypeOverlay">ShowTypeOverlay</a></td><td>
Windows VISTA and above only. 

`true` (`True` in Visual Basic) indicates a thumbnail should show the application that would be invoked when opening the item, 

`false` (`False` in Visual Basic) indicates that no application will be shown.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_WebView">WebView</a></td><td>
`true` (`True` in Visual Basic) to display as a web view.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_WinXpStartPanelOn">WinXpStartPanelOn</a></td><td>
Windows XP only. 

`true` (`True` in Visual Basic) to use the Windows XP-style Start menu, `false` (`False` in Visual Basic) to use the classic Start menu.</td></tr></table>&nbsp;
<a href="#shellstate-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_FirstFlags">FirstFlags</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_NotUsed">NotUsed</a></td><td>
Not used.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ParamSort">ParamSort</a></td><td>
The column to sort by.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_SecondFlags">SecondFlags</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_SortDirection">SortDirection</a></td><td>
Alphabetical sort direction for the column specified by lParamSort. 

 Use 1 for an ascending sort, -1 for a descending sort.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_Version">Version</a></td><td>
Not used.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_Win95Unused1">Win95Unused1</a></td><td>
Not used.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_Win95Unused2">Win95Unused2</a></td><td>
Not used.</td></tr></table>&nbsp;
<a href="#shellstate-structure">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#shellstate-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/bb759788%28v=VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/bb759788%28v=VS.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />