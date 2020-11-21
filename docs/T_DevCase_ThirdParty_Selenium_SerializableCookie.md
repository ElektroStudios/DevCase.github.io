# SerializableCookie Class
 

Represents a cookie in the browser that can be serialized and deserialized.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;Cookie<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Selenium.SerializableCookie<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("Cookie")]
public sealed class SerializableCookie : Cookie
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("Cookie")>
Public NotInheritable Class SerializableCookie
	Inherits Cookie
```

**VB Usage**<br />
``` VB Usage
Dim instance As SerializableCookie
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"Cookie")]
public ref class SerializableCookie sealed : public Cookie
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("Cookie")>]
type SerializableCookie =  
    class
        inherit Cookie
    end
```

The SerializableCookie type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Selenium_SerializableCookie__ctor">SerializableCookie(String, String)</a></td><td>
Initializes a new instance of the SerializableCookie class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Selenium_SerializableCookie__ctor_1">SerializableCookie(String, String, String)</a></td><td>
Initializes a new instance of the SerializableCookie class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Selenium_SerializableCookie__ctor_2">SerializableCookie(String, String, String, Nullable(DateTime))</a></td><td>
Initializes a new instance of the SerializableCookie class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Selenium_SerializableCookie__ctor_3">SerializableCookie(String, String, String, String, Nullable(DateTime))</a></td><td>
Initializes a new instance of the SerializableCookie class.</td></tr></table>&nbsp;
<a href="#serializablecookie-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_Selenium_SerializableCookie_op_Implicit">Implicit(ReturnedCookie to SerializableCookie)</a></td><td>
Performs an implicit conversion from ReturnedCookie to SerializableCookie.</td></tr></table>&nbsp;
<a href="#serializablecookie-class">Back to Top</a>

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
<a href="#serializablecookie-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium Namespace</a><br />