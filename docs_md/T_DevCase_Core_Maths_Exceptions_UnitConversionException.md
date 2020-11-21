# UnitConversionException Class
 

Exception thrown when a unit conversion failed, i.e. because you are converting amounts from one unit into another non-compatible unit.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Exception<br />&nbsp;&nbsp;&nbsp;&nbsp;System.SystemException<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.InvalidOperationException<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Maths.Exceptions.UnitConversionException<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Exceptions">DevCase.Core.Maths.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("UnitConversionException")]
public class UnitConversionException : InvalidOperationException
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("UnitConversionException")>
Public Class UnitConversionException
	Inherits InvalidOperationException
```

**VB Usage**<br />
``` VB Usage
Dim instance As UnitConversionException
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"UnitConversionException")]
public ref class UnitConversionException : public InvalidOperationException
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<XmlRootAttribute("UnitConversionException")>]
type UnitConversionException =  
    class
        inherit InvalidOperationException
    end
```

The UnitConversionException type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Exceptions_UnitConversionException__ctor">UnitConversionException()</a></td><td>
Initializes a new instance of the UnitConversionException class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Exceptions_UnitConversionException__ctor_2">UnitConversionException(String)</a></td><td>
Initializes a new instance of the UnitConversionException class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Exceptions_UnitConversionException__ctor_3">UnitConversionException(String, Exception)</a></td><td>
Initializes a new instance of the UnitConversionException class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Exceptions_UnitConversionException__ctor_1">UnitConversionException(Unit, Unit)</a></td><td>
Initializes a new instance of the UnitConversionException class.</td></tr></table>&nbsp;
<a href="#unitconversionexception-class">Back to Top</a>

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
<a href="#unitconversionexception-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Maths_Exceptions">DevCase.Core.Maths.Exceptions Namespace</a><br />