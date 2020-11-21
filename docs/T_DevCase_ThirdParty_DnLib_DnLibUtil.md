# DnLibUtil Class
 

Contains DnLib related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.DnLib.DnLibUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class DnLibUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class DnLibUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As DnLibUtil
```

**C++**<br />
``` C++
public ref class DnLibUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DnLibUtil =  
    class
        inherit AestheticObject
    end
```

The DnLibUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DnLib_DnLibUtil_AssemblyHasNativeCode">AssemblyHasNativeCode(ModuleDef)</a></td><td>
Determines whether a .NET assembly has native code (C++/CLI).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DnLib_DnLibUtil_AssemblyHasNativeCode_1">AssemblyHasNativeCode(String)</a></td><td>
Determines whether a .NET Assembly has native code (C++/CLI).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DnLib_DnLibUtil_GetCLRVersion">GetCLRVersion(ModuleDefMD)</a></td><td>
Gets the CLR runtime version of a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DnLib_DnLibUtil_GetCLRVersion_1">GetCLRVersion(String)</a></td><td>
Gets the CLR runtime version of a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DnLib_DnLibUtil_GetMethods">GetMethods(ModuleDefMD, String)</a></td><td>
Gets all the Methods defined in a existing Type inside a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DnLib_DnLibUtil_GetMethods_1">GetMethods(String, String)</a></td><td>
Gets all the Methods defined in a existing Type inside a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DnLib_DnLibUtil_GetTypes">GetTypes(ModuleDefMD)</a></td><td>
Gets all the Types defined (including nested Types) inside a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DnLib_DnLibUtil_GetTypes_1">GetTypes(String)</a></td><td>
Gets all the Types defined (including nested Types) inside a .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DnLib_DnLibUtil_LoadAssembly">LoadAssembly</a></td><td>
Loads an Assembly into a ModuleDefMD instance.</td></tr></table>&nbsp;
<a href="#dnlibutil-class">Back to Top</a>

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
<a href="#dnlibutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib Namespace</a><br />