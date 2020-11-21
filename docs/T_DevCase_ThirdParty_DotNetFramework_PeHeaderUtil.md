# PeHeaderUtil Class
 

Contains PE header related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.DotNetFramework.PeHeaderUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class PeHeaderUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class PeHeaderUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As PeHeaderUtil
```

**C++**<br />
``` C++
public ref class PeHeaderUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PeHeaderUtil =  
    class
        inherit AestheticObject
    end
```

The PeHeaderUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetPEFileKind">GetPEFileKind(FileInfo)</a></td><td>
Gets the PEFileKinds of the specified .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetPEFileKind_1">GetPEFileKind(String)</a></td><td>
Gets the PEFileKinds of the specified .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetPEHeader">GetPEHeader(FileInfo)</a></td><td>
Gets the PE header of the specified .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetPEHeader_1">GetPEHeader(String)</a></td><td>
Gets the PE header of the specified .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetTimeStamp">GetTimeStamp(FileInfo)</a></td><td>
Gets the compilation timestamp of the specified .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetTimeStamp_1">GetTimeStamp(String)</a></td><td>
Gets the compilation timestamp of the specified .NET assembly.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_IsStrongNameSigned">IsStrongNameSigned(FileInfo)</a></td><td>
Gets a value that determine whether the specified .NET assembly is strong-name signed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_IsStrongNameSigned_1">IsStrongNameSigned(String)</a></td><td>
Gets a value that determine whether the specified .NET assembly is strong-name signed.</td></tr></table>&nbsp;
<a href="#peheaderutil-class">Back to Top</a>

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
<a href="#peheaderutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework Namespace</a><br />