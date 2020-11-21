# ServiceDependancyDisabledException Class
 

Exception that is thrown when a service cannot start because a dependant service is disabled.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Exception<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticException">DevCase.Core.Design.AestheticException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Exceptions.ServiceDependancyDisabledException<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Exceptions">DevCase.Core.Shell.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("ServiceDependancyDisabledException")]
public sealed class ServiceDependancyDisabledException : AestheticException
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("ServiceDependancyDisabledException")>
Public NotInheritable Class ServiceDependancyDisabledException
	Inherits AestheticException
```

**VB Usage**<br />
``` VB Usage
Dim instance As ServiceDependancyDisabledException
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"ServiceDependancyDisabledException")]
public ref class ServiceDependancyDisabledException sealed : public AestheticException
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("ServiceDependancyDisabledException")>]
type ServiceDependancyDisabledException =  
    class
        inherit AestheticException
    end
```

The ServiceDependancyDisabledException type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException__ctor">ServiceDependancyDisabledException</a></td><td>
Initializes a new instance of the ServiceDependancyDisabledException class.</td></tr></table>&nbsp;
<a href="#servicedependancydisabledexception-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException_DependancyService">DependancyService</a></td><td>
Gets the dependancy service.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException_Message">Message</a></td><td>
Gets a message that describes the current exception.
 (Overrides Exception.Message.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException_Service">Service</a></td><td>
Gets the service.</td></tr></table>&nbsp;
<a href="#servicedependancydisabledexception-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException_GetObjectData">GetObjectData</a></td><td>
Populates a SerializationInfo with the data needed to serialize the target object.
 (Overrides Exception.GetObjectData(SerializationInfo, StreamingContext).)</td></tr></table>&nbsp;
<a href="#servicedependancydisabledexception-class">Back to Top</a>

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
<a href="#servicedependancydisabledexception-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Exceptions">DevCase.Core.Shell.Exceptions Namespace</a><br />