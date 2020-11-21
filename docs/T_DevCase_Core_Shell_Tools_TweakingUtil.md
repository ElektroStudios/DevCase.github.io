# TweakingUtil Class
 

Contains system-parameter related tweaking utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.TweakingUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class TweakingUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class TweakingUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As TweakingUtil
```

**C++**<br />
``` C++
public ref class TweakingUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type TweakingUtil =  
    class
        inherit AestheticObject
    end
```

The TweakingUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_AcceleratorKeysEnabled">AcceleratorKeysEnabled</a></td><td>
Gets or sets a value that determines whether the accelerator keys are enabled. 

 The accelerator keys are visible underlined characters in some menus.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ActiveWindowTrackingEnabled">ActiveWindowTrackingEnabled</a></td><td>
Gets or sets a value that determines whether active window tracking (activating the window the mouse is on) is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ActiveWindowTrackingTimeout">ActiveWindowTrackingTimeout</a></td><td>
Gets or sets the active window tracking delay, in milliseconds.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_AeroPeekEnabled">AeroPeekEnabled</a></td><td>
Gets or sets a value that determines whether Aero Peek (preview desktop) is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_AutoEndTasks">AutoEndTasks</a></td><td>
Gets or sets a value that determines whether user processes end automatically when the user either logs off or shuts down.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_AutomaticNetworkDiscoveryEnabled">AutomaticNetworkDiscoveryEnabled</a></td><td>
Gets or sets a value that determines whether the automatic searching for network folders and printers is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_BeepEnabled">BeepEnabled</a></td><td>
Gets or sets a value that determines whether system beep is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_BingSearchEnabled">BingSearchEnabled</a></td><td>
Gets or sets a value that determines whether Bing search is enabled in Windows searcher. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_BlockSendInputResetsEnabled">BlockSendInputResetsEnabled</a></td><td>
Gets or sets a value that determines whether an application can reset the screensaver's timer by calling the SendInput function to simulate keyboard or mouse input.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_BorderMultiplierFactor">BorderMultiplierFactor</a></td><td>
Gets or sets the border multiplier factor that determines the width of a window's sizing border.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_CaretWidth">CaretWidth</a></td><td>
Gets or sets the width, in pixels, of the caret in edit controls.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_CleartypeEnabled">CleartypeEnabled</a></td><td>
Gets or sets a value that determines whether ClearType feature is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ClientAreaAnimationEnabled">ClientAreaAnimationEnabled</a></td><td>
Gets or sets a value that determines whether animation effects in the client area of applications are enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_CombineSystemTrayIcons">CombineSystemTrayIcons</a></td><td>
Gets or sets a value that determines whether icons are combined in the SysTray.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_CombineTaskbarApplications">CombineTaskbarApplications</a></td><td>
Gets or sets a value that determines whether applications are combined in the Taskbar.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ComboBoxAnimationEnabled">ComboBoxAnimationEnabled</a></td><td>
Gets or sets a value that determines whether the slide-open effect for combo boxes is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ComputerName">ComputerName</a></td><td>
Gets or sets the computer name for the current machine. 

 Note that the name change do not take effect until the user restarts the computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ConfirmRecycle">ConfirmRecycle</a></td><td>
Gets or sets a value that determines whether the system will show a confirmation dialog box when deleting items to the Recycle Bin.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ConsoleBackColor">ConsoleBackColor</a></td><td>
Gets or sets the background color of the CMD.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ConsoleBufferAmount">ConsoleBufferAmount</a></td><td>
Gets or sets the amount of buffers of the CMD, valid range is from `1` to `999`.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ConsoleBufferSize">ConsoleBufferSize</a></td><td>
Gets or sets the buffer size of the CMD, valid range is from `1` to `999`.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ConsoleEditEnabled">ConsoleEditEnabled</a></td><td>
Gets or sets a value that determines whether quick edit is enabled in the CMD.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ConsoleForeColor">ConsoleForeColor</a></td><td>
Gets or sets the foreground color of the CMD.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ConsoleTransparency">ConsoleTransparency</a></td><td>
Gets or sets a value that determines the transparency of the CMD, valid range is from `0.0F` to `1.0F`. 

 This feature is available only in window 10 and the new Console should be enabled, see <a href="P_DevCase_Core_Shell_Tools_TweakingUtil_Consolev2Enabled">Consolev2Enabled</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_Consolev2Enabled">Consolev2Enabled</a></td><td>
Gets or sets a value that determines whether the new Console (CMD) is enabled in Windows. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_CortanaEnabled">CortanaEnabled</a></td><td>
Gets or sets a value that determines whether Cortana is enabled in Windows. 

 Note that this DOESN'T uninstall Cortana, just disable it. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_CortanaSearchBoxEnabled">CortanaSearchBoxEnabled</a></td><td>
Gets or sets a value that determines whether Cortana search box is shown in the Taskbar. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_CortanaSearchEnabled">CortanaSearchEnabled</a></td><td>
Gets or sets a value that determines whether Cortana search is enabled in Windows searcher. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_CursorShadowEnabled">CursorShadowEnabled</a></td><td>
Gets or sets a value that determines whether the cursor has a shadow around it.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DefaultTTL">DefaultTTL</a></td><td>
Gets or sets a value that specifies the default Time to Live (TTL) value in the header of outgoing IP packets. 

 The TTL determines how long an IP packet that has not reached its destination can remain on the network before it is discarded.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DefragBootOptimizeEnabled">DefragBootOptimizeEnabled</a></td><td>
Gets or sets a value that determines whether Defragmentation's Boot optimization is enabled. 

 Windows automatically optimizes the file location for boot optimization. This optimization occurs automatically if the system is idle for 10 minutes. 

 Boot optimization improves startup time by locating startup files in contiguous clusters on the volume, reducing the movement of the disk head when reading the volume.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DefragOptimalLayoutEnabled">DefragOptimalLayoutEnabled</a></td><td>
Gets or sets a value that determines whether Defragmentation's Optimal Layout is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DesktopAutoColorizationEnabled">DesktopAutoColorizationEnabled</a></td><td>
Gets or sets a value that determines whether the desktop auto colorizes itself based on the predominant color of the current wallpaper.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DesktopLivePreviewHoverTime">DesktopLivePreviewHoverTime</a></td><td>
Gets or sets a value that determines the time it takes for Aero Peek to display when you hover over its icon in the far right of the Taskbar.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DoubleClickSize">DoubleClickSize</a></td><td>
Gets or sets the width and height, in pixels, of the double-click rectangle which the second click of a double-click must fall for it to be registered as a double-click.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DoubleClickTime">DoubleClickTime</a></td><td>
Gets or sets the maximum number of milliseconds that can occur between the first and second clicks of a double-click.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DragFullWindowsEnabled">DragFullWindowsEnabled</a></td><td>
Gets or sets a value that enables or disables dragging of full windows.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DragSize">DragSize</a></td><td>
Gets or sets the width and height, in pixels, of the rectangle used to detect the start of a drag operation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_DropShadowEnabled">DropShadowEnabled</a></td><td>
Gets or sets a value that determines whether drop shadow effect feature is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ExplorerNavigationPanelEnabled">ExplorerNavigationPanelEnabled</a></td><td>
Gets or sets a value that determines whether navigation panel (left pane) is enabled in Explorer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ExtendedPathsEnabled">ExtendedPathsEnabled</a></td><td>
Gets or sets a value that determines whether the extended-length paths is enabled on the current drive. 

 In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_FileCheckboxSelectionEnabled">FileCheckboxSelectionEnabled</a></td><td>
Gets or sets a value that determines whether the checkbox folder view is enabled in Explorer, this way the user can select all items with a checkbox.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_FileThumbnailPreviewEnabled">FileThumbnailPreviewEnabled</a></td><td>
Gets or sets a value that determines whether the system should create thumbnails for preview files. 

 If disabled, the system will generate generic icons only.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_FiletypeOverlayEnabled">FiletypeOverlayEnabled</a></td><td>
Gets or sets a value that determines whether a thumbnail should show the application that would be invoked when opening a Explorer item.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_FlatMenuEnabled">FlatMenuEnabled</a></td><td>
Gets or sets a value that determines whether flat menu appearance for native User menus are enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_FocusBorderSize">FocusBorderSize</a></td><td>
Gets or sets the width and height, in pixels, of the focus rectangle drawn with DrawFocusRect.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_FolderMergeConflictDialogEnabled">FolderMergeConflictDialogEnabled</a></td><td>
Gets or sets a value that determines whether a conflict dialog will be shown when trying to merge folders.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_FontSmoothingContrast">FontSmoothingContrast</a></td><td>
Gets or sets the contrast value used in ClearType smoothing. From 1000 to 2200.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_FontSmoothingEnabled">FontSmoothingEnabled</a></td><td>
Gets or sets a value that enables or disables the font smoothing feature, which uses font antialiasing to make font curves appear smoother by painting pixels at different gray levels.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ForegroundFlashCount">ForegroundFlashCount</a></td><td>
Gets or sets the number of times SetForegroundWindow will flash the taskbar button when rejecting a foreground switch request.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ForegroundLockTimeout">ForegroundLockTimeout</a></td><td>
Gets or sets the amount of time following user input, in milliseconds, during which the system will not allow applications to force themselves into the foreground.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_HideDrivesWithNoMedia">HideDrivesWithNoMedia</a></td><td>
Gets or sets a value that determines whether drives with no media inserted will be hidden in Explorer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_HotCornerTopLeftEnabled">HotCornerTopLeftEnabled</a></td><td>
Gets or sets a value that determines whether the top-left hot corner is enabled in the desktop.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_HotCornerTopRightEnabled">HotCornerTopRightEnabled</a></td><td>
Gets or sets a value that determines whether the top-right hot corner is enabled in the desktop.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_HotTrackingEnabled">HotTrackingEnabled</a></td><td>
Gets or sets a value that determines whether hot tracking of user-interface elements such as menu names on menu bars is enabled. Hot-tracking means that when the cursor moves over an item, it is highlighted but not selected.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_HungAppTimeout">HungAppTimeout</a></td><td>
Gets or sets the number of milliseconds that a thread can go without dispatching a message before the system considers it unresponsive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_IconSpacing">IconSpacing</a></td><td>
Gets or sets the width and height, in pixels, of an icon cell.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_IconTitleWrappingEnabled">IconTitleWrappingEnabled</a></td><td>
Gets or sets a value that determines whether icon-title wrapping is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_InfoTipEnabled">InfoTipEnabled</a></td><td>
Gets or sets a value that determines whether pop-up description for folders and files is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_InstallDate">InstallDate</a></td><td>
Gets or sets the installation date of the current operating system of this computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_KeyboardDelay">KeyboardDelay</a></td><td>
Gets or sets the keyboard repeat-delay. From 0 to 3. Where zero sets the shortest delay (approximately 250 ms) and 3 sets the longest delay (approximately 1 second).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_KeyboardSpeed">KeyboardSpeed</a></td><td>
Gets or sets the keyboard repeat-speed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ListBoxSmoothScrollingEnabled">ListBoxSmoothScrollingEnabled</a></td><td>
Gets or sets a value that determines whether the smooth-scrolling effect for list boxes is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_LowDiskFreeSpaceNotificationEnabled">LowDiskFreeSpaceNotificationEnabled</a></td><td>
Gets or sets a value that determines whether a popup will be shown when a hard disk has low disk free space available.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MenuAccessKeysUnderlined">MenuAccessKeysUnderlined</a></td><td>
Gets or sets a value that determines whether underlining of menu access key letters is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MenuAnimationEnabled">MenuAnimationEnabled</a></td><td>
Gets or sets a value that determines whether menu animations are enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MenuFadeEnabled">MenuFadeEnabled</a></td><td>
Gets or sets a value that determines whether menu fade animation is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MenuShowDelay">MenuShowDelay</a></td><td>
Gets or sets the time, in milliseconds, that the system waits before displaying a cascaded shortcut menu when the mouse cursor is over a submenu item.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MessageDuration">MessageDuration</a></td><td>
Gets or sets the time that notification pop-ups should be displayed, in seconds.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MinAnimate">MinAnimate</a></td><td>
Gets or sets a value that determines whether a window animates while being resized.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MinimumSelectedItemsToInvokeMenu">MinimumSelectedItemsToInvokeMenu</a></td><td>
Gets or sets a value that determines the minimum items selected in the Explorer to show context menu options that are associated with the selected file extension(s). 

 Valid range is from `1` to `2.147.483.647` (or Int32). 

 Default system value is `15`.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseButtonsSwapEnabled">MouseButtonsSwapEnabled</a></td><td>
Gets or sets a value that swaps or restores the meaning of the left and right mouse buttons.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseClickLockEnabled">MouseClickLockEnabled</a></td><td>
Gets or sets a value that determines whether mouse clicklock feature is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseClickLockTime">MouseClickLockTime</a></td><td>
Gets or sets the time delay before the primary mouse button is locked.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseHoverSize">MouseHoverSize</a></td><td>
Gets or sets the width and height, in pixels, of the rectangle which the mouse pointer has to stay for TrackMouseEvent to generate a WM_MOUSEHOVER message.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseHoverTime">MouseHoverTime</a></td><td>
Gets or sets the time, in milliseconds, that the mouse pointer has to stay in the hover rectangle for TrackMouseEvent to generate a WM_MOUSEHOVER message.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseSonarEnabled">MouseSonarEnabled</a></td><td>
Gets or sets a value that determines whether mouse sonar feature is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseSpeed">MouseSpeed</a></td><td>
Gets or sets the current mouse speed. From 1 to 20.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseTrailAmount">MouseTrailAmount</a></td><td>
Gets or sets the number of cursors drawn when mouse trail feature is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseTrailEnabled">MouseTrailEnabled</a></td><td>
Gets or sets a value that determines whether cursor movements shows a trail of cursors.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseVanishEnabled">MouseVanishEnabled</a></td><td>
Gets or sets a value that determines whether mouse vanish feature is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MouseWheelScrollLines">MouseWheelScrollLines</a></td><td>
Gets or sets the number of lines to scroll when the mouse wheel is rotated.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_MyPCDisplayName">MyPCDisplayName</a></td><td>
Gets or sets the display name for `MyPC` folder.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_NoSimpleNetIDList">NoSimpleNetIDList</a></td><td>
Gets or sets a value that determines whether network files or folders are automatically refreshed after you create, move or delete files or folders.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_NotepadWordwrapEnabled">NotepadWordwrapEnabled</a></td><td>
Gets or sets a value that determines whether wordwrap is enabled in Notepad.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_NotificationCenterEnabled">NotificationCenterEnabled</a></td><td>
Gets or sets a value that determines whether Notification Center is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_OemLogo">OemLogo</a></td><td>
Gets or sets the logo field of the OEM information of this computer. 

 For example: C:\Windows\System32\OEMLogo.bmp</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_OemManufacturer">OemManufacturer</a></td><td>
Gets or sets the manufacturer name of the OEM information of this computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_OemModel">OemModel</a></td><td>
Gets or sets the model name of the OEM information of this computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_OemSupportHours">OemSupportHours</a></td><td>
Gets or sets the support hours field of the OEM information of this computer. 

 For example: 24x7x365</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_OemSupportPhone">OemSupportPhone</a></td><td>
Gets or sets the support phone field of the OEM information of this computer. 

 For example: (842) 555-4335</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_OemSupportUrl">OemSupportUrl</a></td><td>
Gets or sets the support phone field of the OEM information of this computer. 

 For example: http://www.domain.com/</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_OverlappedContentEnabled">OverlappedContentEnabled</a></td><td>
Gets or sets a value that determines whether overlapped content is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_PopupMenuAlignment">PopupMenuAlignment</a></td><td>
Gets or sets the side of pop-up menus that are aligned to the corresponding menu-bar item.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ProductId">ProductId</a></td><td>
Gets or sets the product identifier of this computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ProductName">ProductName</a></td><td>
Gets or sets the product name of this computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_RegisteredOrganization">RegisteredOrganization</a></td><td>
Gets or sets the registered organization name of this computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_RegisteredOwner">RegisteredOwner</a></td><td>
Gets or sets the registered owner name of this computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_RunExplorerInSeparateProcessEnabled">RunExplorerInSeparateProcessEnabled</a></td><td>
Gets or sets a value that determines whether the system should run Explorer instances in separate processes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ScreensaverEnabled">ScreensaverEnabled</a></td><td>
Gets or sets a value that determines whether screensaver is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ScreensaverTimeout">ScreensaverTimeout</a></td><td>
Gets or sets the screen saver time-out, in seconds. From 1 to 599940.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ScreensaveSecureEnabled">ScreensaveSecureEnabled</a></td><td>
Gets or sets a value that determines whether the screen saver requires a password to display the Windows desktop.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_SecurityCenterNotificationsEnabled">SecurityCenterNotificationsEnabled</a></td><td>
Gets or sets a value that determines whether Security Center will display notifications.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_SelectionFadeEnabled">SelectionFadeEnabled</a></td><td>
Gets or sets a value that determines whether a selected menu item by the user should remain on the screen briefly while fading out after the menu is dismissed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowCompressedFilesColor">ShowCompressedFilesColor</a></td><td>
Gets or sets a value that determines whether the system will show encrypted or compressed NTFS files in different color than normal files.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowDesktopIcons">ShowDesktopIcons</a></td><td>
Gets or sets a value that determines whether the system will show or hide the Desktop icons.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowFilenameExtensions">ShowFilenameExtensions</a></td><td>
Gets or sets a value that determines whether filename extensions are shown.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowFrequentDirsInQuickAccess">ShowFrequentDirsInQuickAccess</a></td><td>
Gets or sets a value that determines whether frequent directories are shown in the Quick Access dialog. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowFullPathInExplorer">ShowFullPathInExplorer</a></td><td>
Gets or sets a value that determines whether full path is shown in Explorer's address bar.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowHiddenFiles">ShowHiddenFiles</a></td><td>
Gets or sets a value that determines whether hidden files and folders are shown.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowOneDriveInFolderBrowser">ShowOneDriveInFolderBrowser</a></td><td>
Gets or sets a value that determines whether `One Drive` is visible in the folder browser dialog. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowOneDriveInMyPC">ShowOneDriveInMyPC</a></td><td>
Gets or sets a value that determines whether `One Drive` is visible in `My PC`. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowQuickAccessInFolderBrowser">ShowQuickAccessInFolderBrowser</a></td><td>
Gets or sets a value that determines whether `Quick Access` is visible in the folder browser dialog. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowQuickAccessInMyPC">ShowQuickAccessInMyPC</a></td><td>
Gets or sets a value that determines whether `Quick Access` is visible in `My PC`. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowRecentItemsInQuickAccess">ShowRecentItemsInQuickAccess</a></td><td>
Gets or sets a value that determines whether recent items are shown in the Quick Access dialog. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowShortcutFileExtension">ShowShortcutFileExtension</a></td><td>
Gets or sets a value that determines whether shortcut files will display the ".lnk" extension.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowShortcutSuffix">ShowShortcutSuffix</a></td><td>
Gets or sets a value that determines whether the suffix "shortcut" is shown for new shortcut files (.lnk).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowSuperHiddenFiles">ShowSuperHiddenFiles</a></td><td>
Gets or sets a value that determines whether the system should show operating system files.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowSystemFiles">ShowSystemFiles</a></td><td> **Obsolete. **
Gets or sets a value that determines whether the system will show system files.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowUrlFileExtension">ShowUrlFileExtension</a></td><td>
Gets or sets a value that determines whether internet shortcut files will display the ".url" extension.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ShowWindowsStorePinnedInTaskbar">ShowWindowsStorePinnedInTaskbar</a></td><td>
Gets or sets a value that determines whether Windows Store pinned item will be shown in Taskbar. 

 This feature is available only in window 10.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_SlowSearchNotificationEnabled">SlowSearchNotificationEnabled</a></td><td>
Gets or sets a value that determines whether Windows Search will display a notification about low searchs, suggesting to enable file indexation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_SnapToDefaultEnabled">SnapToDefaultEnabled</a></td><td>
Gets or sets a value that determines whether the snap-to-default-button feature is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_StatusBarEnabled">StatusBarEnabled</a></td><td>
Gets or sets a value that determines whether the Explorer's status bar is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_SystemDateTime">SystemDateTime</a></td><td>
Gets or sets the system date and time.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_SystemLanguageBarEnabled">SystemLanguageBarEnabled</a></td><td>
Gets or sets a value that determines whether the system language bar is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_TaskbarAnimationsEnabled">TaskbarAnimationsEnabled</a></td><td>
Gets or sets a value that determines whether Defragmentation's Optimal Layout is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_TitleBarGradientEnabled">TitleBarGradientEnabled</a></td><td>
Gets or sets a value that determines whether the gradient effect for window title bars are enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_ToolTipAnimationEnabled">ToolTipAnimationEnabled</a></td><td>
Gets or sets a value that determines whether ToolTip animations are enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_UIEffectsEnabled">UIEffectsEnabled</a></td><td>
Gets or sets a value that determines whether UI effects are enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_WaitToKillAppTimeout">WaitToKillAppTimeout</a></td><td>
Gets or sets the number of milliseconds that the system waits before terminating an application that does not respond to a shutdown request.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_WaitToKillServiceTimeout">WaitToKillServiceTimeout</a></td><td>
Gets or sets the number of milliseconds that the service control manager waits before terminating a service that does not respond to a shutdown request.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_WheelscrollChars">WheelscrollChars</a></td><td>
Gets or sets the number of characters to scroll when the horizontal mouse wheel is moved.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_WindowArrangementEnabled">WindowArrangementEnabled</a></td><td>
Gets or sets a value that determines whether window arrangement is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_TweakingUtil_WindowsErrorReportingEnabled">WindowsErrorReportingEnabled</a></td><td>
Gets or sets a value that determines whether Windows Error Reporting (WER) is enabled.</td></tr></table>&nbsp;
<a href="#tweakingutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_TweakingUtil_RemoveArrowIconOfShortcutFiles">RemoveArrowIconOfShortcutFiles</a></td><td>
This method will remove the arrow icon of (.lnk) shortcut files. 

 A system reboot or user re-logon is required to apply changes.</td></tr></table>&nbsp;
<a href="#tweakingutil-class">Back to Top</a>

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
<a href="#tweakingutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />