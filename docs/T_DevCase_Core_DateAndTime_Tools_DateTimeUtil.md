# DateTimeUtil Class
 

Contains date and time related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.DateAndTime.Tools.DateTimeUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class DateTimeUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class DateTimeUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As DateTimeUtil
```

**C++**<br />
``` C++
public ref class DateTimeUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DateTimeUtil =  
    class
        inherit AestheticObject
    end
```

The DateTimeUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_DateAndTime_Tools_DateTimeUtil_Timestamp">Timestamp</a></td><td>
Gets the current time stamp, in `ISO 8601` format.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_DateAndTime_Tools_DateTimeUtil_Tomorrow">Tomorrow</a></td><td>
Gets the date of tomorrow.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_DateAndTime_Tools_DateTimeUtil_Tomorrow_1">Tomorrow(String)</a></td><td>
Gets the date of tomorrow as a string representation using the specified format.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_DateAndTime_Tools_DateTimeUtil_Tomorrow_2">Tomorrow(String, IFormatProvider)</a></td><td>
Gets the date of tomorrow as a string representation using the specified format and provider.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_DateAndTime_Tools_DateTimeUtil_Yesterday">Yesterday</a></td><td>
Gets the date of yesterday.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_DateAndTime_Tools_DateTimeUtil_Yesterday_1">Yesterday(String)</a></td><td>
Gets the date of yesterday as a string representation using the specified format.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_DateAndTime_Tools_DateTimeUtil_Yesterday_2">Yesterday(String, IFormatProvider)</a></td><td>
Gets the date of yesterday as a string representation using the specified format and provider.</td></tr></table>&nbsp;
<a href="#datetimeutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_ConvertTime">ConvertTime</a></td><td>
Converts between units of time.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_DateDiff">DateDiff</a></td><td>
Calculates the difference between two dates.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetAge">GetAge(DateTime)</a></td><td>
Gets the current years old of a person from the specified birth date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetAge_1">GetAge(DateTime, DateTime)</a></td><td>
Gets the years old of a person at specified date from the specified birth date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetAgeTime">GetAgeTime(DateTime)</a></td><td>
Gets the current elapsed life time of a person from the specified birth date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetAgeTime_1">GetAgeTime(DateTime, DateTime)</a></td><td>
Gets the elapsed life time of a person at specified date from the specified birth date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetRandomDateTime">GetRandomDateTime()</a></td><td>
Gets a random DateTime in range between MinValue and MaxValue.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetRandomDateTime_1">GetRandomDateTime(DateTime)</a></td><td>
Gets a random DateTime in range between MinValue and the specified date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetRandomDateTime_2">GetRandomDateTime(DateTime, DateTime)</a></td><td>
Gets a random DateTime in range between the specified two dates.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_DateAndTime_Tools_DateTimeUtil_TimeDiff">TimeDiff</a></td><td>
Calculates the difference between two intervals of time.</td></tr></table>&nbsp;
<a href="#datetimeutil-class">Back to Top</a>

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
<a href="#datetimeutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />