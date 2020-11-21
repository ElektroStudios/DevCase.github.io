# SystemNotificationUtil Class
 

Notifies the system about changes on the environment to update quickly.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.SystemNotificationUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class SystemNotificationUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class SystemNotificationUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemNotificationUtil
```

**C++**<br />
``` C++
public ref class SystemNotificationUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SystemNotificationUtil =  
    class
        inherit AestheticObject
    end
```

The SystemNotificationUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyDirectoryAttributesChanged">NotifyDirectoryAttributesChanged</a></td><td>
Notifies the system that the attributes of a directory have changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyDirectoryCreated">NotifyDirectoryCreated</a></td><td>
Notifies the system that a directory has been created.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyDirectoryDeleted">NotifyDirectoryDeleted</a></td><td>
Notifies the system that a directory has been deleted.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyDirectoryRenamed">NotifyDirectoryRenamed</a></td><td>
Notifies the system that a directory has been renamed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyDriveAdded">NotifyDriveAdded</a></td><td>
Notifies the system that a drive has been added.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyDriveRemoved">NotifyDriveRemoved</a></td><td>
Notifies the system that a drive has been removed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyFileAssociationChanged">NotifyFileAssociationChanged</a></td><td>
Notifies the system that a file type association has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyFileAttributesChanged">NotifyFileAttributesChanged</a></td><td>
Notifies the system that the attributes of a file have changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyFileCreated">NotifyFileCreated</a></td><td>
Notifies the system that a file has been created.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyFileDeleted">NotifyFileDeleted</a></td><td>
Notifies the system that a file has been deleted.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyFileRenamed">NotifyFileRenamed</a></td><td>
Notifies the system that a file has been renamed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyFreespaceChanged">NotifyFreespaceChanged</a></td><td>
Notifies the system that amount of free space on a drive has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyMediaInserted">NotifyMediaInserted</a></td><td>
Notifies the system that a storage media has been inserted into a drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyMediaRemoved">NotifyMediaRemoved</a></td><td>
Notifies the system that a storage media has been removed from a drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyNetworkFolderShared">NotifyNetworkFolderShared</a></td><td>
Notifies the system that a directory on the local computer is being shared via the network.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyNetworkFolderUnshared">NotifyNetworkFolderUnshared</a></td><td>
Notifies the system that a directory on the local computer is no longer being shared via the network.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyRegistryChange">NotifyRegistryChange</a></td><td>
Notifies the system to update after a registry change.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyUpdateDirectory">NotifyUpdateDirectory</a></td><td>
Notifies the system that the contents of an existing folder have changed but the folder still exists and has not been renamed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_NotifyUpdateImage">NotifyUpdateImage</a></td><td>
Notifies the system that an image in the system image list has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_ReloadSystemCursors">ReloadSystemCursors</a></td><td>
Reloads the system cursors.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SystemNotificationUtil_ReloadSystemIcons">ReloadSystemIcons</a></td><td>
Reloads the system icons.</td></tr></table>&nbsp;
<a href="#systemnotificationutil-class">Back to Top</a>

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
<a href="#systemnotificationutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />