# ExplorerUtil Methods
 

The <a href="T_DevCase_Core_Shell_Tools_ExplorerUtil">ExplorerUtil</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ExplorerUtil_AddItemToRecentDocs">AddItemToRecentDocs</a></td><td>
Adds an item into the Windows recent docs (MRU) list.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Shell_Tools_ExplorerUtil_BlockTaskManager">BlockTaskManager</a></td><td>
Prevents any attempt for the current user from reading and running the 'taskmgr.exe' file and any defined hijack in the system (if any). 

 Note that the file blocking is not permanent. 

 This function will return a FileStream Array that contains the 'taskmgr.exe' file stream(s) opened with Read access and None sharing. 

 So in order to unblock the access to the file(s), just dispose the opened stream(s) or terminate the calling aplication.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ExplorerUtil_ClearRecentDocs">ClearRecentDocs</a></td><td>
Clears all the items in the Windows recent docs (MRU) list.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ExplorerUtil_RebuildIconAndThumbnailCaches">RebuildIconAndThumbnailCaches</a></td><td>
Deletes the operating system's icon and thumbnail cache files. 

 WARNING: calling this method will terminate any "Explorer.exe" running instances.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ExplorerUtil_RebuildIconCache">RebuildIconCache</a></td><td>
Deletes the operating system's icon cache files. 

 WARNING: calling this method will terminate any "Explorer.exe" running instances.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ExplorerUtil_RebuildThumbnailCache">RebuildThumbnailCache</a></td><td>
Deletes the operating system's thumbnail cache files. 

 WARNING: calling this method will terminate any "Explorer.exe" running instances.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ExplorerUtil_RefreshWindows">RefreshWindows</a></td><td>
Refreshes the opened windows explorer folder instances.</td></tr></table>&nbsp;
<a href="#explorerutil-methods">Back to Top</a>

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
<a href="#explorerutil-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ExplorerUtil">ExplorerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />