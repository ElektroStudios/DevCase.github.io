# HotkeyIsNotRegisteredException Class
 

Exception that is thrown when try to unregister a system-wide hotkey that is not registered.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Exception<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticException">DevCase.Core.Design.AestheticException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Exceptions.HotkeyIsNotRegisteredException<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Exceptions">DevCase.Core.Application.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("HotkeyIsNotRegisteredException")]
public sealed class HotkeyIsNotRegisteredException : AestheticException
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("HotkeyIsNotRegisteredException")>
Public NotInheritable Class HotkeyIsNotRegisteredException
	Inherits AestheticException
```

**VB Usage**<br />
``` VB Usage
Dim instance As HotkeyIsNotRegisteredException
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"HotkeyIsNotRegisteredException")]
public ref class HotkeyIsNotRegisteredException sealed : public AestheticException
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("HotkeyIsNotRegisteredException")>]
type HotkeyIsNotRegisteredException =  
    class
        inherit AestheticException
    end
```

The HotkeyIsNotRegisteredException type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Exceptions_HotkeyIsNotRegisteredException__ctor">HotkeyIsNotRegisteredException</a></td><td>
Initializes a new instance of the HotkeyIsNotRegisteredException class.</td></tr></table>&nbsp;
<a href="#hotkeyisnotregisteredexception-class">Back to Top</a>

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
<a href="#hotkeyisnotregisteredexception-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_Exceptions">DevCase.Core.Application.Exceptions Namespace</a><br />