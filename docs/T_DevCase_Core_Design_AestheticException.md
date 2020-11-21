# AestheticException Class
 

This is a class to consume for aesthetic purposes. 

 A default (emptyness) class that inherits from Exception, with these base members hidden: 

GetHashCode(), GetType(), Equals(Object), Equals(Object, Object), ReferenceEquals(Object, Object), ToString().


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Exception<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.AestheticException<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#inheritance-hierarchy">More...</a>
**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[ClassInterfaceAttribute(ClassInterfaceType.None)]
[ComVisibleAttribute(true)]
public abstract class AestheticException : Exception
```

**VB**<br />
``` VB
<SerializableAttribute>
<ClassInterfaceAttribute(ClassInterfaceType.None)>
<ComVisibleAttribute(true)>
Public MustInherit Class AestheticException
	Inherits Exception
```

**VB Usage**<br />
``` VB Usage
Dim instance As AestheticException
```

**C++**<br />
``` C++
[SerializableAttribute]
[ClassInterfaceAttribute(ClassInterfaceType::None)]
[ComVisibleAttribute(true)]
public ref class AestheticException abstract : public Exception
```

**F#**<br />
``` F#
[<AbstractClassAttribute>]
[<SerializableAttribute>]
[<ClassInterfaceAttribute(ClassInterfaceType.None)>]
[<ComVisibleAttribute(true)>]
type AestheticException =  
    class
        inherit Exception
    end
```

The AestheticException type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_AestheticException__ctor">AestheticException()</a></td><td>
Initializes a new instance of the AestheticException class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_AestheticException__ctor_1">AestheticException(String)</a></td><td>
Initializes a new instance of the AestheticException class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_AestheticException__ctor_2">AestheticException(String, Exception)</a></td><td>
Initializes a new instance of the AestheticException class.</td></tr></table>&nbsp;
<a href="#aestheticexception-class">Back to Top</a>

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
<a href="#aestheticexception-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />

## Inheritance HierarchySystem.Object<br />&nbsp;&nbsp;System.Exception<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.AestheticException<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Application_Exceptions_HotkeyIsNotRegisteredException">DevCase.Core.Application.Exceptions.HotkeyIsNotRegisteredException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Application_Exceptions_HotkeyIsRegisteredException">DevCase.Core.Application.Exceptions.HotkeyIsRegisteredException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Multimedia_Gaming_Exceptions_InvalidSnesRomFormatException">DevCase.Core.Multimedia.Gaming.Exceptions.InvalidSnesRomFormatException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_Exceptions_BBCodeHtmlRenderException">DevCase.Core.NET.Exceptions.BBCodeHtmlRenderException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_Exceptions_BBCodeParseException">DevCase.Core.NET.Exceptions.BBCodeParseException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_Exceptions_DisposableMailExpiredException">DevCase.Core.NET.Exceptions.DisposableMailExpiredException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException">DevCase.Core.Shell.Exceptions.ServiceDependancyDisabledException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_VmWare_Exceptions_VmRunException">DevCase.ThirdParty.VmWare.Exceptions.VmRunException</a><br />