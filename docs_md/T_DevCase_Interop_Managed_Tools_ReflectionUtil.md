# ReflectionUtil Class
 

Contains Reflection related utilites.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Interop.Managed.Tools.ReflectionUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ReflectionUtil
```

**VB**<br />
``` VB
Public NotInheritable Class ReflectionUtil
```

**VB Usage**<br />
``` VB Usage
Dim instance As ReflectionUtil
```

**C++**<br />
``` C++
public ref class ReflectionUtil sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ReflectionUtil =  class end
```

The ReflectionUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllBaseTypes__1">GetAllBaseTypes(T)</a></td><td>
Gets the Type inheritance hierarchy of the the source Type, that is, the type from which the source Type directly inherits, and the types from which their inherited types inherits.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllConstructors">GetAllConstructors(Object, BindingFlags)</a></td><td>
Gets all the constructors declared in the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllConstructors_1">GetAllConstructors(Type, BindingFlags)</a></td><td>
Gets all the constructors declared in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllConstructors__1">GetAllConstructors(T)(BindingFlags)</a></td><td>
Gets all the constructors declared in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllDerivedTypes__1">GetAllDerivedTypes(T)()</a></td><td>
Gets all the types that inherits from the source Type within the Assembly in which the source Type is defined.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllDerivedTypes__1_1">GetAllDerivedTypes(T)(Assembly)</a></td><td>
Gets all the types that inherits from the source Type within the specified Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllEnums">GetAllEnums</a></td><td>
Gets all the Enum types defined in the source Assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllFields">GetAllFields(Object, Boolean, BindingFlags)</a></td><td>
Gets all the fields declared in the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllFields_1">GetAllFields(Type, Boolean, BindingFlags)</a></td><td>
Gets all the fields declared in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllFields__1">GetAllFields(T)(Boolean, BindingFlags)</a></td><td>
Gets all the fields declared in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllInterfaces">GetAllInterfaces(Object)</a></td><td>
Gets all the interfaces implemented or inherited by the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllInterfaces_1">GetAllInterfaces(Type)</a></td><td>
Gets all the interfaces implemented or inherited by the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllInterfaces__1">GetAllInterfaces(T)()</a></td><td>
Gets all the interfaces implemented or inherited by the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllMethods">GetAllMethods(Object, Boolean, BindingFlags)</a></td><td>
Gets all the methods declared in the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllMethods_1">GetAllMethods(Type, Boolean, BindingFlags)</a></td><td>
Gets all the methods declared in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllMethods__1">GetAllMethods(T)(Boolean, BindingFlags)</a></td><td>
Gets all the methods declared in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllProperties">GetAllProperties(Object, Boolean, BindingFlags)</a></td><td>
Gets all the properties declared in the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllProperties_1">GetAllProperties(Type, Boolean, BindingFlags)</a></td><td>
Gets all the properties declared in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllProperties__1">GetAllProperties(T)(Boolean, BindingFlags)</a></td><td>
Gets all the properties declared in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAssemblyPEKind">GetAssemblyPEKind</a></td><td>
Determines the PE (Portable Executable) type of a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAssemblyTargetPlatform">GetAssemblyTargetPlatform</a></td><td>
Determines the target platform (i386, AMD64, etc) of a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetCLRVersion">GetCLRVersion</a></td><td>
Gets the CLR runtime version on which the specified assembly runs on.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetField">GetField(Object, String, BindingFlags)</a></td><td>
Searches for the specified field in the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetField_1">GetField(Type, String, BindingFlags)</a></td><td>
Searches for the specified field in the specified type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetField__1">GetField(T)(String, BindingFlags)</a></td><td>
Searches for the specified field in the specified type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetFieldValue__1">GetFieldValue(T)(Object, String, BindingFlags)</a></td><td>
Searches for the specified field in the specified object, and returns the field value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetFieldValue__1_1">GetFieldValue(T)(Object, String, T, BindingFlags)</a></td><td>
Searches for the specified field in the specified object, and returns the field value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetInterface">GetInterface(Object, String)</a></td><td>
Searches for the specified interface implemented or inherited in the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetInterface_1">GetInterface(Type, String)</a></td><td>
Searches for the specified interface implemented or inherited in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetInterface__1">GetInterface(T)(String)</a></td><td>
Searches for the specified interface implemented or inherited in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetMethod">GetMethod(Object, String, BindingFlags)</a></td><td>
Searches for the target method in the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetMethod_1">GetMethod(Object, String, Type[])</a></td><td>
Searches for the target method in the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetMethod_2">GetMethod(Type, String, BindingFlags)</a></td><td>
Searches for the target method in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetMethod_3">GetMethod(Type, String, Type[])</a></td><td>
Searches for the target method in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetProperty">GetProperty(Object, String, BindingFlags)</a></td><td>
Searches for the specified property in the specified object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetProperty_1">GetProperty(Type, String, BindingFlags)</a></td><td>
Searches for the specified property in the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetProperty__1">GetProperty(T)(String, BindingFlags)</a></td><td>
Searches for the specified property in the specified type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetPropertyValue__1">GetPropertyValue(T)(Object, String, BindingFlags)</a></td><td>
Searches for the specified property in the specified object, and returns the property value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetPropertyValue__1_1">GetPropertyValue(T)(Object, String, T, BindingFlags)</a></td><td>
Searches for the specified property in the specified object, and returns the property value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetReferencedAssemblies">GetReferencedAssemblies</a></td><td>
Gets the referenced assemblies of the specified assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetTargetFrameworkName">GetTargetFrameworkName</a></td><td>
Gets the display name of the .NET Framework version on which the source assembly was compiled.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_GetTargetFrameworkVersion">GetTargetFrameworkVersion</a></td><td>
Gets the .NET Framework version on which the specified assembly was compiled.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_IsNetAssembly">IsNetAssembly</a></td><td>
Determines whether an exe/dll file is an .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_TypeHasPublicConstructor">TypeHasPublicConstructor</a></td><td>
Determines whether the source Type has defined at least one public constructor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Managed_Tools_ReflectionUtil_TypeHasPublicDefaultConstructor">TypeHasPublicDefaultConstructor</a></td><td>
Determines whether the source Type has defined a public default parameterless constructor.</td></tr></table>&nbsp;
<a href="#reflectionutil-class">Back to Top</a>

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
<a href="#reflectionutil-class">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa383751%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa383751%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />