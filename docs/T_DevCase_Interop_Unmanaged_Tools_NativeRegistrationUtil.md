# NativeRegistrationUtil Class
 

Contains related COM registration utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Interop.Unmanaged.Tools.NativeRegistrationUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class NativeRegistrationUtil
```

**VB**<br />
``` VB
Public NotInheritable Class NativeRegistrationUtil
```

**VB Usage**<br />
``` VB Usage
Dim instance As NativeRegistrationUtil
```

**C++**<br />
``` C++
public ref class NativeRegistrationUtil sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
type NativeRegistrationUtil =  class end
```

The NativeRegistrationUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil_RegisterNativeDll">RegisterNativeDll(FileInfo)</a></td><td>
Registers the classes in a native dll to enable creation from COM. 

 This is the equivalent for calling `RegSvr32.exe` to register a native dll.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil_RegisterNativeDll_1">RegisterNativeDll(String)</a></td><td>
Registers the classes in a native dll to enable creation from COM. 

 This is the equivalent for calling `RegSvr32.exe` to register a native dll.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil_UnregisterNativeDll">UnregisterNativeDll(FileInfo)</a></td><td>
Unregisters the classes in a native dll. 

 This is the equivalent for calling `RegSvr32.exe` to unregister a native dll.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil_UnregisterNativeDll_1">UnregisterNativeDll(String)</a></td><td>
Unregisters the classes in a native dll. 

 This is the equivalent for calling `RegSvr32.exe` to unregister a native dll.</td></tr></table>&nbsp;
<a href="#nativeregistrationutil-class">Back to Top</a>

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
<a href="#nativeregistrationutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />