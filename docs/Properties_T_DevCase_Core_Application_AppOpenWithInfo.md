# AppOpenWithInfo Properties
 

The <a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo</a> type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_DefaultIcon">DefaultIcon</a></td><td>
Gets or sets the default icon to represent the application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_FriendlyAppName">FriendlyAppName</a></td><td>
Gets or sets the localizable name to display for an application instead of just the version information appearing, which may not be localizable. 

 The association query ASSOCSTR reads this registry entry value and falls back to use the FileDescription name in the version information. If that name is missing, the association query defaults to the display name of the file. 

 Applications should use ASSOCSTR_FRIENDLYAPPNAME to retrieve this information to obtain the proper behavior.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_IsHostApp">IsHostApp</a></td><td>
Gets or sets a value indicating whether the process is a host process, such as Rundll32.exe or Dllhost.exe, and should not be considered for Start menu pinning or inclusion in the Most Frequently Used (MFU) list. 

 When launched with a shortcut that contains a non-null argument list or an explicit Application User Model IDs (AppUserModelIDs), the process can be pinned (as that shortcut). Such shortcuts are candidates for inclusion in the MFU list.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_NoOpenWith">NoOpenWith</a></td><td>
Gets or sets a value indicating whether cc. 

 Be aware that if an OpenWithProgIDs subkey has been set for an application by file type, and the ProgID subkey itself does not also have a NoOpenWith entry, that application will appear in the list of recommended or available applications even if it has specified the NoOpenWith entry.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_NoStartPage">NoStartPage</a></td><td>
Gets or sets a value indicating whether the application executable and shortcuts should be excluded from the Start menu and from pinning or inclusion in the MFU list. 

 This entry is typically used to exclude system tools, installers and uninstallers, and readme files.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_SupportedTypes">SupportedTypes</a></td><td>
Gets or sets the file types that the application supports. 

 Doing so enables the application to be listed in the cascade menu of the Open with dialog box.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_TaskbarGroupIcon">TaskbarGroupIcon</a></td><td>
Gets or sets the icon used to override the taskbar icon. The window icon is normally used for the taskbar. 

 Setting the TaskbarGroupIcon entry causes the system to use the icon from the .exe for the application instead.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_UseExecutableForTaskbarGroupIcon">UseExecutableForTaskbarGroupIcon</a></td><td>
Gets or sets a value indicating whether to use the default icon of this executable in the taskbar if there is no pinnable shortcut for this application, and instead of the icon of the window that was first encountered.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_Verb">Verb</a></td><td>
Gets or sets the verb method for calling the application from OpenWith menu. 

 Without a verb definition specified here, the system assumes that the application supports CreateProcess, and passes the file name on the command line. 

 This functionality applies to all the verb methods, including DropTarget, ExecuteCommand, and Dynamic Data Exchange (DDE).</td></tr></table>&nbsp;
<a href="#appopenwithinfo-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />