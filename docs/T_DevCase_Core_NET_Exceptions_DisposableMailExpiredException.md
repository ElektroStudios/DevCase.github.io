# DisposableMailExpiredException Class
 

Represents a error that occur when attempting to have access to a expired disposable mail represented by the <a href="T_DevCase_Core_NET_IDisposableMail">IDisposableMail</a> interface.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Exception<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticException">DevCase.Core.Design.AestheticException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.Exceptions.DisposableMailExpiredException<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[ClassInterfaceAttribute(ClassInterfaceType.None)]
[ComVisibleAttribute(true)]
public sealed class DisposableMailExpiredException : AestheticException
```

**VB**<br />
``` VB
<SerializableAttribute>
<ClassInterfaceAttribute(ClassInterfaceType.None)>
<ComVisibleAttribute(true)>
Public NotInheritable Class DisposableMailExpiredException
	Inherits AestheticException
```

**VB Usage**<br />
``` VB Usage
Dim instance As DisposableMailExpiredException
```

**C++**<br />
``` C++
[SerializableAttribute]
[ClassInterfaceAttribute(ClassInterfaceType::None)]
[ComVisibleAttribute(true)]
public ref class DisposableMailExpiredException sealed : public AestheticException
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<ClassInterfaceAttribute(ClassInterfaceType.None)>]
[<ComVisibleAttribute(true)>]
type DisposableMailExpiredException =  
    class
        inherit AestheticException
    end
```

The DisposableMailExpiredException type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_Exceptions_DisposableMailExpiredException__ctor">DisposableMailExpiredException()</a></td><td>
Initializes a new instance of the DisposableMailExpiredException class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_Exceptions_DisposableMailExpiredException__ctor_1">DisposableMailExpiredException(String)</a></td><td>
Initializes a new instance of the DisposableMailExpiredException class with a specified error message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_Exceptions_DisposableMailExpiredException__ctor_2">DisposableMailExpiredException(String, Exception)</a></td><td>
Initializes a new instance of the DisposableMailExpiredException class with a specified error message.</td></tr></table>&nbsp;
<a href="#disposablemailexpiredexception-class">Back to Top</a>

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
<a href="#disposablemailexpiredexception-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions Namespace</a><br />