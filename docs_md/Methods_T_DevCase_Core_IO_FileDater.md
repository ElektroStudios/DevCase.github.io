# FileDater Methods
 

The <a href="T_DevCase_Core_IO_FileDater">FileDater</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Restore">Restore</a></td><td>
Restores the specified saved dates on the file. 

 Note: Calling this method does not cause the removal of any saved date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Save">Save</a></td><td>
Preserves the specified dates of the file to restore them later at any time. 

 Note: Dates can be preserved again at any time.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Set">Set</a></td><td>
Sets the specified dates on the file. 

 Note: Calling this method does not cause the removal of any saved date. 

 After setting a date, must call once the <a href="M_DevCase_Core_IO_FileDater_Save">Save(DateAttribute)</a> method if want to save any date established.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_SetFilepath">SetFilepath(FileInfo)</a></td><td>
Causes this <a href="T_DevCase_Core_IO_FileDater">FileDater</a> instance to assign a new location for the current file. 

 This could be useful if the saved dates should be restored in a file that has changed its name/ubication. 

 Note: Calling this method does not cause the removal of any saved date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_SetFilepath_1">SetFilepath(String)</a></td><td>
Causes this <a href="T_DevCase_Core_IO_FileDater">FileDater</a> instance to assign a new location for the current file. 

 This could be useful if the saved dates should be restored in a file that has changed its name/ubication. 

 Note: Calling this method does not cause the removal of any saved date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Truncate">Truncate</a></td><td>
Truncates the specified date(s) of the file to "01/01/1800 00:00:00". 

 Note: Calling this method does not cause the removal of any saved date. 

 After setting a date, must call once the <a href="M_DevCase_Core_IO_FileDater_Save">Save(DateAttribute)</a> method if want to save any date established.</td></tr></table>&nbsp;
<a href="#filedater-methods">Back to Top</a>

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
<a href="#filedater-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileDater">FileDater Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />