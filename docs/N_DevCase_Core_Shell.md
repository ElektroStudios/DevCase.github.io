# DevCase.Core.Shell Namespace
 




## Classes
&nbsp;<table><tr><th></th><th>Class</th><th>Description</th></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders</a></td><td>
Provides access to special environment folders and their directory paths.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo</a></td><td>
Defines the system information of a file extension.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Shell_HostsMappingInfo">HostsMappingInfo</a></td><td>
Defines the info of a Windows Hosts-file mapping.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Shell_PowerPlan">PowerPlan</a></td><td>
Represents a Power Plan.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Shell_PowerStateMonitor">PowerStateMonitor</a></td><td>
Monitors the system and battery power-state activity. 

 Suscribe to the events exposed by this class to be notifies about power-state changes.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Shell_PreventShutdownContext">PreventShutdownContext</a></td><td>
Provides a mechanism to prevent any system shutdown/restart/log-off request during the life-cycle of a instance of this class. 

 Applications should use this class as they begin an operation that cannot be interrupted, such as burning a CD or DVD. 

 This class is to be used in either a `Using` statement or for the life-cycle of the current application.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Shell_RegInfo">RegInfo</a></td><td>
Defines the info of a registry key.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T)</a></td><td>
Defines the info of a registry key of a specific type.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Shell_ThemeInfo">ThemeInfo</a></td><td>
Defines the information of a Windows Visual Theme.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Shell_VariableInfo">VariableInfo</a></td><td>
Defines the info of a Windows environment Variable.</td></tr></table>

## Enumerations
&nbsp;<table><tr><th></th><th>Enumeration</th><th>Description</th></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_CmdCommandRedirection">CmdCommandRedirection</a></td><td>
Specifies a CMD output to redirect commands.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_ControlPanelItems">ControlPanelItems</a></td><td>
Specifies a Control Panel item. 

 This list corresponds to Windows 10's control panel items.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_DesktopIconViewMode">DesktopIconViewMode</a></td><td>
Specifies the view mode of the desktop icons.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_ItemVerbs">ItemVerbs</a></td><td>
A verb is a string used to specify a particular action that an item supports. 

 Invoking a verb is equivalent to selecting a command from an item's context menu. 

 Typically, invoking a verb launches a related application. For example, invoking the "open" verb on a ".txt" file opens the file with a text editor, usually Notepad.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_LogOffMode">LogOffMode</a></td><td>
Specifies the mode to logoff an user session.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_MonitorState">MonitorState</a></td><td>
Specifies a monitor state.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_OsArchitecture">OsArchitecture</a></td><td>
Specifies a Windows operating system architecture.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_RecycleFlags">RecycleFlags</a></td><td>
Specifies the system's Recycle Bin behavior when cleaning the bin.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_RegistryScope">RegistryScope</a></td><td>
Specifies a registry scope (a root key).</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_RegistryValueType">RegistryValueType</a></td><td>
Specifies the data type of a registry value.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_ServiceStartModeEx">ServiceStartModeEx</a></td><td>
Specifies the start mode of a service.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_ServiceStatus">ServiceStatus</a></td><td>
Specifies the status of a service.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_ShutdownMode">ShutdownMode</a></td><td>
Specifies the mode to shutdown/restart the system.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_ShutdownPlanning">ShutdownPlanning</a></td><td>
Specifies a shutdown planning.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_ShutdownReason">ShutdownReason</a></td><td>
Specifies a shutdown/restart reason.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_SystemScope">SystemScope</a></td><td>
Specifies a system scope.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_TaskbarPosition">TaskbarPosition</a></td><td>
Specifies a position for the Windows taskbar.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_TaskbarState">TaskbarState</a></td><td>
Specifies a Windows taskbar state.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_TaskBarVisibility">TaskBarVisibility</a></td><td>
Specifies the visibility for a TaskBar window.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_WallpaperStyle">WallpaperStyle</a></td><td>
Describes a wallpaper style.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Shell_WinStartupScope">WinStartupScope</a></td><td>
Specifies a Windows Startup scope.</td></tr></table>&nbsp;
