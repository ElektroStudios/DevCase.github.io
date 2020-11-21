# ResourceUtil Methods
 

The <a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_Execute">Execute(Byte[])</a></td><td>
Loads a resource in memory and executes its main entrypoint. 

 The resource must be a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_Execute_1">Execute(Byte[], Object[])</a></td><td>
Loads a resource in memory and executes its main entrypoint. 

 The resource must be a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_ExecuteSafe">ExecuteSafe(Byte[])</a></td><td>
Loads a resource in memory and executes its main entrypoint. 

 The resource must be a .NET assembly. 

 If the loaded assembly attempts to force an application termination by for example internaly calling Exit(Int32), then the call is catched and ignored. 

 The downside is that the loaded assembly will not be able to call (P/Invoke) unmanaged code. You are advised. 

 *** Note that this is a experimental methodology. ***</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_ExecuteSafe_1">ExecuteSafe(Byte[], Object[])</a></td><td>
Loads a resource in memory and executes its main entrypoint. 

 The resource must be a .NET assembly. 

 If the loaded assembly attempts to force an application termination by for example internaly calling Exit(Int32), then the call is catched and ignored. 

 The downside is that the loaded assembly will not be able to call (P/Invoke) unmanaged code. You are advised. 

 *** Note that this is a experimental methodology. ***</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_ExtractResourceToDisk">ExtractResourceToDisk</a></td><td>
Extracts a resource to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResource">GetEmbeddedResource(String)</a></td><td>
Gets an embedded resource in the calling assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResource_1">GetEmbeddedResource(String, Assembly)</a></td><td>
Gets an embedded resource in the specified Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResourceAsImage">GetEmbeddedResourceAsImage(String)</a></td><td>
Gets an embedded resource of type Image in the calling assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResourceAsImage_1">GetEmbeddedResourceAsImage(String, Assembly)</a></td><td>
Gets an embedded resource of type Image in the specified Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResourceAsString_1">GetEmbeddedResourceAsString(String, Encoding)</a></td><td>
Gets an embedded resource of type String in the calling assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResourceAsString">GetEmbeddedResourceAsString(String, Assembly, Encoding)</a></td><td>
Gets an embedded resource of type String in the specified Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_GetResourcesOf__1">GetResourcesOf(T)</a></td><td>
Gets the resources of the specified type in the calling assembly.</td></tr></table>&nbsp;
<a href="#resourceutil-methods">Back to Top</a>

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
<a href="#resourceutil-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />