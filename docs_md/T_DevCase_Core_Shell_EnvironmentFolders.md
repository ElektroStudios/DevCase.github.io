# EnvironmentFolders Class
 

Provides access to special environment folders and their directory paths.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.EnvironmentFolders<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class EnvironmentFolders : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class EnvironmentFolders
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As EnvironmentFolders
```

**C++**<br />
``` C++
public ref class EnvironmentFolders sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type EnvironmentFolders =  
    class
        inherit AestheticObject
    end
```

The EnvironmentFolders type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_AdminToolsDirectory">AdminToolsDirectory</a></td><td>
Gets the file system directory that is used to store administrative tools for an individual user. 

 The Microsoft Management Console (MMC) will save customized consoles to this directory, and it will roam with the user. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Administrative Tools'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_AdminToolsPath">AdminToolsPath</a></td><td>
Gets the full path to the file system directory that is used to store administrative tools for an individual user. 

 The Microsoft Management Console (MMC) will save customized consoles to this directory, and it will roam with the user. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Administrative Tools'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ApplicationDataDirectory">ApplicationDataDirectory</a></td><td>
Gets the directory that serves as a common repository for application-specific data for the current roaming user. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ApplicationDataPath">ApplicationDataPath</a></td><td>
Gets the full path to the directory that serves as a common repository for application-specific data for the current roaming user. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CDBurningDirectory">CDBurningDirectory</a></td><td>
Gets the file system directory that acts as a staging area for files waiting to be written to a CD. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\Burn\Burn'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CDBurningPath">CDBurningPath</a></td><td>
Gets the full path to the file system directory that acts as a staging area for files waiting to be written to a CD. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\Burn\Burn'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonAdminToolsDirectory">CommonAdminToolsDirectory</a></td><td>
Gets the file system directory that contains administrative tools for all users of the compute. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Administrative Tools'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonAdminToolsPath">CommonAdminToolsPath</a></td><td>
Gets the full path to the file system directory that contains administrative tools for all users of the computer. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Administrative Tools'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonApplicationDataDirectory">CommonApplicationDataDirectory</a></td><td>
Gets the directory that serves as a common repository for application-specific data that is used by all users. 

 Typically: 'C:\ProgramData'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonApplicationDataPath">CommonApplicationDataPath</a></td><td>
Gets the full path to the directory that serves as a common repository for application-specific data that is used by all users. 

 Typically: 'C:\ProgramData'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonDesktopDirectory">CommonDesktopDirectory</a></td><td>
Gets the file system directory that contains files and folders that appear on the desktop for all users. 

 Typically: 'C:\Users\Public\Desktop'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonDesktopPath">CommonDesktopPath</a></td><td>
Gets the full path to the file system directory that contains files and folders that appear on the desktop for all users. 

 Typically: 'C:\Users\Public\Desktop'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonDocumentsDirectory">CommonDocumentsDirectory</a></td><td>
Gets the file system directory that contains documents that are common to all users. 

 Typically: 'C:\Users\Public\Documents'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonDocumentsPath">CommonDocumentsPath</a></td><td>
Gets the full path to the file system directory that contains documents that are common to all users. 

 Typically: 'C:\Users\Public\Documents'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonMusicDirectory">CommonMusicDirectory</a></td><td>
Gets the file system directory that serves as a repository for music files common to all users. 

 Typically: 'C:\Users\Public\Music'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonMusicPath">CommonMusicPath</a></td><td>
Gets the full path to the file system directory that serves as a repository for music files common to all users. 

 Typically: 'C:\Users\Public\Music'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonPicturesDirectory">CommonPicturesDirectory</a></td><td>
Gets the file system directory that serves as a repository for image files common to all users. 

 Typically: 'C:\Users\Public\Pictures'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonPicturesPath">CommonPicturesPath</a></td><td>
Gets the full path to the file system directory that serves as a repository for image files common to all users. 

 Typically: 'C:\Users\Public\Pictures'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonProgramFilesDirectory">CommonProgramFilesDirectory</a></td><td>
Gets the the directory for components that are shared across applications. 

 Typically: 'C:\Program Files\Common Files'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonProgramFilesPath">CommonProgramFilesPath</a></td><td>
Gets the full path to the directory for components that are shared across applications. 

 Typically: 'C:\Program Files\Common Files'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonProgramFilesX86Directory">CommonProgramFilesX86Directory</a></td><td>
Gets the the Program Files folder. 

 Typically: 'C:\Program Files (x86)\Common Files'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonProgramFilesX86Path">CommonProgramFilesX86Path</a></td><td>
Gets the full path to the Program Files folder. 

 Typically: 'C:\Program Files (x86)\Common Files'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonProgramsDirectory">CommonProgramsDirectory</a></td><td>
Gets the folder for components that are shared across applications. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu\Programs'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonProgramsPath">CommonProgramsPath</a></td><td>
Gets the full path to the folder for components that are shared across applications. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu\Programs'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonStartMenuDirectory">CommonStartMenuDirectory</a></td><td>
Gets the file system directory that contains the programs and folders that appear on the Start menu for all users. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonStartMenuPath">CommonStartMenuPath</a></td><td>
Gets the full path to the file system directory that contains the programs and folders that appear on the Start menu for all users. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonStartupDirectory">CommonStartupDirectory</a></td><td>
Gets the file system directory that contains the programs that appear in the Startup folder for all users. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonStartupPath">CommonStartupPath</a></td><td>
Gets the full path to the file system directory that contains the programs that appear in the Startup folder for all users. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonTemplatesDirectory">CommonTemplatesDirectory</a></td><td>
Gets the file system directory that contains the templates that are available to all users. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Templates'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonTemplatesPath">CommonTemplatesPath</a></td><td>
Gets the full path to the file system directory that contains the templates that are available to all users. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Templates'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonVideosDirectory">CommonVideosDirectory</a></td><td>
Gets the file system directory that serves as a repository for video files common to all users. 

 Typically: 'C:\Users\Public\Videos'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CommonVideosPath">CommonVideosPath</a></td><td>
Gets the full path to the file system directory that serves as a repository for video files common to all users. 

 Typically: 'C:\Users\Public\Videos'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CookiesDirectory">CookiesDirectory</a></td><td>
Gets the directory that serves as a common repository for Internet cookies. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\INetCookies'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_CookiesPath">CookiesPath</a></td><td>
Gets the full path to the directory that serves as a common repository for Internet cookies. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\INetCookies'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_DesktopDirectory">DesktopDirectory</a></td><td>
Gets the directory used to physically store file objects on the desktop. 

 Typically: 'C:\Users\{USERNAME}\Desktop'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_DesktopPath">DesktopPath</a></td><td>
Gets the full path to the directory used to physically store file objects on the desktop. 

 Typically: 'C:\Users\{USERNAME}\Desktop'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_FavoritesDirectory">FavoritesDirectory</a></td><td>
Gets the directory that serves as a common repository for the user's favorite items. 

 Typically: 'C:\Users\{USERNAME}\Favorites'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_FavoritesPath">FavoritesPath</a></td><td>
Gets the full path to the directory that serves as a common repository for the user's favorite items. 

 Typically: 'C:\Users\{USERNAME}\Favorites'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_FontsDirectory">FontsDirectory</a></td><td>
Gets the virtual folder that contains fonts. 

 Typically: 'C:\Windows\Fonts'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_FontsPath">FontsPath</a></td><td>
Gets the full path to the virtual folder that contains fonts. 

 Typically: 'C:\Windows\Fonts'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_HistoryDirectory">HistoryDirectory</a></td><td>
Gets the directory that serves as a common repository for Internet history items. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\History'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_HistoryPath">HistoryPath</a></td><td>
Gets the full path to the directory that serves as a common repository for Internet history items. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\History'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_InternetCacheDirectory">InternetCacheDirectory</a></td><td>
Gets the directory that serves as a common repository for temporary Internet files. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\INetCache'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_InternetCachePath">InternetCachePath</a></td><td>
Gets the full path to the directory that serves as a common repository for temporary Internet files. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\INetCache'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_LocalApplicationDataDirectory">LocalApplicationDataDirectory</a></td><td>
Gets the directory that serves as a common repository for application-specific data that is used by the current, non-roaming user. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_LocalApplicationDataPath">LocalApplicationDataPath</a></td><td>
Gets the full path to the directory that serves as a common repository for application-specific data that is used by the current, non-roaming user. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_LocalizedResourcesDirectory">LocalizedResourcesDirectory</a></td><td>
Gets the file system directory that contains localized resource data.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_LocalizedResourcesPath">LocalizedResourcesPath</a></td><td>
Gets the full path to the file system directory that contains localized resource data.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_MyDocumentsDirectory">MyDocumentsDirectory</a></td><td>
Gets the My Documents folder. 

 Typically: 'C:\Users\{USERNAME}\Documents'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_MyDocumentsPath">MyDocumentsPath</a></td><td>
Gets the full path to the My Documents folder. 

 Typically: 'C:\Users\{USERNAME}\Documents'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_MyMusicDirectory">MyMusicDirectory</a></td><td>
Gets the My Music folder. 

 Typically: 'C:\Users\{USERNAME}\Music'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_MyMusicPath">MyMusicPath</a></td><td>
Gets the full path to the My Music folder. 

 Typically: 'C:\Users\{USERNAME}\Music'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_MyPicturesDirectory">MyPicturesDirectory</a></td><td>
Gets the My Pictures folder. 

 Typically: 'C:\Users\{USERNAME}\Pictures'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_MyPicturesPath">MyPicturesPath</a></td><td>
Gets the full path to the My Pictures folder. 

 Typically: 'C:\Users\{USERNAME}\Pictures'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_MyVideosDirectory">MyVideosDirectory</a></td><td>
Gets the file system directory that serves as a repository for videos that belong to a user. 

 Typically: 'C:\Users\{USERNAME}\Videos'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_MyVideosPath">MyVideosPath</a></td><td>
Gets the full path to the file system directory that serves as a repository for videos that belong to a user. 

 Typically: 'C:\Users\{USERNAME}\Videos'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_NetworkShortcutsDirectory">NetworkShortcutsDirectory</a></td><td>
Gets the file system directory that contains the link objects that may exist in the My Network Places virtual folder. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Network Shortcuts'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_NetworkShortcutsPath">NetworkShortcutsPath</a></td><td>
Gets the full path to the file system directory that contains the link objects that may exist in the My Network Places virtual folder. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Network Shortcuts'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_PersonalDirectory">PersonalDirectory</a></td><td>
Gets the directory that serves as a common repository for documents. 

 Typically: 'C:\Users\{USERNAME}\Documents'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_PersonalPath">PersonalPath</a></td><td>
Gets the full path to the directory that serves as a common repository for documents. 

 Typically: 'C:\Users\{USERNAME}\Documents'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_PrinterShortcutsDirectory">PrinterShortcutsDirectory</a></td><td>
Gets the file system directory that contains the link objects that can exist in the Printers virtual folder. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Printer Shortcuts'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_PrinterShortcutsPath">PrinterShortcutsPath</a></td><td>
Gets the full path to the file system directory that contains the link objects that can exist in the Printers virtual folder. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Printer Shortcuts'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ProgramFilesDirectory">ProgramFilesDirectory</a></td><td>
Gets the program files directory. 

 Typically: 'C:\Program Files'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ProgramFilesPath">ProgramFilesPath</a></td><td>
Gets the full path to the program files directory. 

 Typically: 'C:\Program Files'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ProgramFilesX86Directory">ProgramFilesX86Directory</a></td><td>
Gets the x86 Program Files folder. 

 Typically: 'C:\Program Files (x86)'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ProgramFilesX86Path">ProgramFilesX86Path</a></td><td>
Gets the full path to the x86 Program Files folder. 

 Typically: 'C:\Program Files (x86)'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ProgramsDirectory">ProgramsDirectory</a></td><td>
Gets the directory that contains the user's program groups. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ProgramsPath">ProgramsPath</a></td><td>
Gets the full path to the directory that contains the user's program groups. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_RecentDirectory">RecentDirectory</a></td><td>
Gets the directory that contains the user's most recently used documents. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Recent'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_RecentPath">RecentPath</a></td><td>
Gets the full path to the directory that contains the user's most recently used documents. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Recent'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ResourcesDirectory">ResourcesDirectory</a></td><td>
Gets the file system directory that contains resource data. 

 Typically: 'C:\Windows\resources'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_ResourcesPath">ResourcesPath</a></td><td>
Gets the full path to the file system directory that contains resource data. 

 Typically: 'C:\Windows\resources'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_SendToDirectory">SendToDirectory</a></td><td>
Gets the directory that contains the Send To menu items. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\SendTo'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_SendToPath">SendToPath</a></td><td>
Gets the full path to the directory that contains the Send To menu items. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\SendTo'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_StartMenuDirectory">StartMenuDirectory</a></td><td>
Gets the directory that contains the Start menu items. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_StartMenuPath">StartMenuPath</a></td><td>
Gets the full path to the directory that contains the Start menu items. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_StartupDirectory">StartupDirectory</a></td><td>
Gets the directory that corresponds to the user's Startup program group. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_StartupPath">StartupPath</a></td><td>
Gets the full path to the directory that corresponds to the user's Startup program group. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_SystemDirectory">SystemDirectory</a></td><td>
Gets the System directory. 

 Typically: 'C:\Windows\System32'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_SystemPath">SystemPath</a></td><td>
Gets the full path to the System directory. 

 Typically: 'C:\Windows\System32'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_SystemX86Directory">SystemX86Directory</a></td><td>
Gets the Windows System folder. 

 Typically: 'C:\Windows\SysWOW64'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_SystemX86Path">SystemX86Path</a></td><td>
Gets the full path to the Windows System folder. 

 Typically: 'C:\Windows\SysWOW64'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_TemplatesDirectory">TemplatesDirectory</a></td><td>
Gets the directory that serves as a common repository for document templates. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Templates'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_TemplatesPath">TemplatesPath</a></td><td>
Gets the full path to the directory that serves as a common repository for document templates. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Templates'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_UserProfileDirectory">UserProfileDirectory</a></td><td>
Gets the user's profile folder. 

 Typically: 'C:\Users\{USERNAME}'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_UserProfilePath">UserProfilePath</a></td><td>
Gets the full path to the user's profile folder. 

 Typically: 'C:\Users\{USERNAME}'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_WindowsDirectory">WindowsDirectory</a></td><td>
Gets the Windows directory or SYSROOT. 

 Typically: 'C:\Windows'</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_EnvironmentFolders_WindowsPath">WindowsPath</a></td><td>
Gets the full path to Windows directory or SYSROOT. 

 Typically: 'C:\Windows'</td></tr></table>&nbsp;
<a href="#environmentfolders-class">Back to Top</a>

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
<a href="#environmentfolders-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />