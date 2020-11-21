# BBCodeHtmlRenderException Class
 

Exception that is thrown when a BBCode document cannot be converted to Html.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Exception<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticException">DevCase.Core.Design.AestheticException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.Exceptions.BBCodeHtmlRenderException<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("BBCodeHtmlRenderException")]
public sealed class BBCodeHtmlRenderException : AestheticException
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("BBCodeHtmlRenderException")>
Public NotInheritable Class BBCodeHtmlRenderException
	Inherits AestheticException
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeHtmlRenderException
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"BBCodeHtmlRenderException")]
public ref class BBCodeHtmlRenderException sealed : public AestheticException
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("BBCodeHtmlRenderException")>]
type BBCodeHtmlRenderException =  
    class
        inherit AestheticException
    end
```

The BBCodeHtmlRenderException type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_Exceptions_BBCodeHtmlRenderException__ctor">BBCodeHtmlRenderException()</a></td><td>
Initializes a new instance of the BBCodeHtmlRenderException class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_Exceptions_BBCodeHtmlRenderException__ctor_1">BBCodeHtmlRenderException(String)</a></td><td>
Initializes a new instance of the BBCodeHtmlRenderException class.</td></tr></table>&nbsp;
<a href="#bbcodehtmlrenderexception-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_Exceptions_BBCodeHtmlRenderException_GetObjectData">GetObjectData</a></td><td>
Populates a SerializationInfo with the data needed to serialize the target object.
 (Overrides Exception.GetObjectData(SerializationInfo, StreamingContext).)</td></tr></table>&nbsp;
<a href="#bbcodehtmlrenderexception-class">Back to Top</a>

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
<a href="#bbcodehtmlrenderexception-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions Namespace</a><br />