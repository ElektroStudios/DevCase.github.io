# ULongExtensions Class
 

Contains custom extension methods to use with the UInt64 type.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.ULong.ULongExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ULong">DevCase.Core.Extensions.ULong</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class ULongExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class ULongExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As ULongExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class ULongExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type ULongExtensions =  class end
```

The ULongExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_DifferenceOf">DifferenceOf</a></td><td>
Gets the difference between the source value and the specified value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_Formatted">Formatted(UInt64)</a></td><td>
Formats a value by placing dots or commas in the corresponding positions depending on the specified culture.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_Formatted_1">Formatted(UInt64, Int32)</a></td><td>
Formats a value by placing dots or commas in the corresponding positions depending on the specified culture.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_Formatted_2">Formatted(UInt64, Int32, CultureInfo)</a></td><td>
Formats a value by placing dots or commas in the corresponding positions depending on the specified culture.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_FractionBy">FractionBy</a></td><td>
Takes a fraction of the source value that corresponds to the given percent value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_IsDivisibleBy">IsDivisibleBy</a></td><td>
Determines whether the source value is divisible by the given value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_IsEven">IsEven</a></td><td>
Determines whether the value is a even number.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_IsInRangeOf">IsInRangeOf</a></td><td>
Determines whether the source value is in range of the given *min* and *max* values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_IsMultipleOf">IsMultipleOf</a></td><td>
Determines whether the source value is a multiple of the given value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_IsNegative">IsNegative</a></td><td>
Determines whether the value is a negative number.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_IsOdd">IsOdd</a></td><td>
Determines whether the value is a odd number.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_IsPositive">IsPositive</a></td><td>
Determines whether the value is a positive number.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_PercentageOf">PercentageOf</a></td><td>
Given a total number, calculates which percentage of is the source value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_ULong_ULongExtensions_ToUIntPtr">ToUIntPtr</a></td><td>
Converts a UInt64 value to an UIntPtr.</td></tr></table>&nbsp;
<a href="#ulongextensions-class">Back to Top</a>

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
<a href="#ulongextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_ULong">DevCase.Core.Extensions.ULong Namespace</a><br />