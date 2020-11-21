# BBCodeParseException Class
 

Exception that is thrown when a BBCode document cannot be parsed.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Exception<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticException">DevCase.Core.Design.AestheticException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.Exceptions.BBCodeParseException<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("BBCodeParseException")]
public sealed class BBCodeParseException : AestheticException
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("BBCodeParseException")>
Public NotInheritable Class BBCodeParseException
	Inherits AestheticException
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeParseException
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"BBCodeParseException")]
public ref class BBCodeParseException sealed : public AestheticException
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("BBCodeParseException")>]
type BBCodeParseException =  
    class
        inherit AestheticException
    end
```

The BBCodeParseException type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_Exceptions_BBCodeParseException__ctor">BBCodeParseException</a></td><td>
Initializes a new instance of the <a href="T_DevCase_Core_NET_Exceptions_BBCodeHtmlRenderException">BBCodeHtmlRenderException</a> class.</td></tr></table>&nbsp;
<a href="#bbcodeparseexception-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_Exceptions_BBCodeParseException_Position">Position</a></td><td>
Gets the position of the character which caused the parse error.</td></tr></table>&nbsp;
<a href="#bbcodeparseexception-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_Exceptions_BBCodeParseException_GetObjectData">GetObjectData</a></td><td>
Populates a SerializationInfo with the data needed to serialize the target object.
 (Overrides Exception.GetObjectData(SerializationInfo, StreamingContext).)</td></tr></table>&nbsp;
<a href="#bbcodeparseexception-class">Back to Top</a>

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
<a href="#bbcodeparseexception-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions Namespace</a><br />