# AssemblyExtensions Methods
 

The <a href="T_DevCase_Core_Extensions_Assembly_AssemblyExtensions">AssemblyExtensions</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_FindRootNamespace">FindRootNamespace</a></td><td>
Tries to detect the root namespace name of the source Assembly. 

 Note that an assembly does not necessarily should have defined a root namespace, and also <a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_FindRootNamespace">FindRootNamespace(Assembly)</a> could return a wrong root namespace name in some circumstances.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_GetDefaultCulture">GetDefaultCulture</a></td><td>
Gets the default CultureInfo (if any) of the source Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_GetDefaultDllImportSearchPaths">GetDefaultDllImportSearchPaths</a></td><td>
Gets the default DllImportSearchPath flags (if any) of the source Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_GetEmbeddedResource">GetEmbeddedResource</a></td><td>
Gets an embedded resource from the source Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_GetGuid">GetGuid</a></td><td>
Gets the assembly Guid (if any) of the source Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_GetLoadableTypes">GetLoadableTypes</a></td><td>
Gets the types defined in the specified a Assembly, only the types that can be loaded. 

 The types that cannot be loaded (eg. due to a missing 3rd party assembly reference) are not returned.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_GetSecurityPermission">GetSecurityPermission</a></td><td>
Gets the SecurityPermissionAttribute (if any) of the source Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_GetTargetFrameworkName">GetTargetFrameworkName</a></td><td>
Gets the display name of the target .NET Framework version on which the source assembly was compiled.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_GetTargetFrameworkVersion">GetTargetFrameworkVersion</a></td><td>
Gets the target .NET Framework version on which the source assembly was compiled.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_IsCLSCompliant">IsCLSCompliant</a></td><td>
Gets a value that determine whether the source Assembly is marked as CLS compliant.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_IsCOMVisible">IsCOMVisible</a></td><td>
Gets a value that determine whether the source Assembly is marked as COM visible.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_IsDpiAwarenessDisabled">IsDpiAwarenessDisabled</a></td><td>
Gets a value that determine whether the source Assembly has disabled dots per inch (DPI) awareness for all user interface elements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_IsStrongNameSigned">IsStrongNameSigned</a></td><td>
Gets a value that determine whether the source Assembly is strong-name signed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Assembly_AssemblyExtensions_ToAssemblyBuilder">ToAssemblyBuilder</a></td><td>
Converts the specified a Assembly to a AssemblyBuilder.</td></tr></table>&nbsp;
<a href="#assemblyextensions-methods">Back to Top</a>

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
<a href="#assemblyextensions-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Assembly_AssemblyExtensions">AssemblyExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly Namespace</a><br />