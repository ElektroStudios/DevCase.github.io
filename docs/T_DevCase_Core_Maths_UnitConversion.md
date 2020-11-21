# UnitConversion Class
 

Represents a conversion between two <a href="T_DevCase_Core_Maths_Unit">Unit</a>.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Maths.UnitConversion<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class UnitConversion : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class UnitConversion
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As UnitConversion
```

**C++**<br />
``` C++
public ref class UnitConversion sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type UnitConversion =  
    class
        inherit AestheticObject
    end
```

The UnitConversion type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_UnitConversion__ctor">UnitConversion</a></td><td>
Initializes a new instance of the UnitConversion class.</td></tr></table>&nbsp;
<a href="#unitconversion-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_UnitConversion_ConversionFunction">ConversionFunction</a></td><td>
Gets the conversion function used to convert the <a href="T_DevCase_Core_Maths_Amount">Amount</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_UnitConversion_FromUnitName">FromUnitName</a></td><td>
Gets the name of the <a href="T_DevCase_Core_Maths_Unit">Unit</a> to convert from.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_UnitConversion_ToUnitName">ToUnitName</a></td><td>
Gets the name of the <a href="T_DevCase_Core_Maths_Unit">Unit</a> to convert to.</td></tr></table>&nbsp;
<a href="#unitconversion-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_UnitConversion_Convert">Convert</a></td><td>
Converts the specified <a href="T_DevCase_Core_Maths_Amount">Amount</a> using the specified conversion function in <a href="P_DevCase_Core_Maths_UnitConversion_ConversionFunction">ConversionFunction</a>.</td></tr></table>&nbsp;
<a href="#unitconversion-class">Back to Top</a>

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
<a href="#unitconversion-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />