# Unit Class
 

Represents a metric unit.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Maths.Unit<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
public sealed class Unit : AestheticObject, IComparable, 
	IComparable<Unit>, IEquatable<Unit>, IFormattable
```

**VB**<br />
``` VB
<SerializableAttribute>
Public NotInheritable Class Unit
	Inherits AestheticObject
	Implements IComparable, IComparable(Of Unit), 
	IEquatable(Of Unit), IFormattable
```

**VB Usage**<br />
``` VB Usage
Dim instance As Unit
```

**C++**<br />
``` C++
[SerializableAttribute]
public ref class Unit sealed : public AestheticObject, 
	IComparable, IComparable<Unit^>, IEquatable<Unit^>, 
	IFormattable
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
type Unit =  
    class
        inherit AestheticObject
        interface IComparable
        interface IComparable<Unit>
        interface IEquatable<Unit>
        interface IFormattable
    end
```

The Unit type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit__ctor">Unit(String, String, MetricUnitType)</a></td><td>
Initializes a new instance of the Unit class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit__ctor_2">Unit(String, String, Unit)</a></td><td>
Initializes a new instance of the Unit class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit__ctor_1">Unit(String, String, MetricUnitType, UnitConversion[])</a></td><td>
Initializes a new instance of the Unit class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit__ctor_3">Unit(String, String, Unit, UnitConversion[])</a></td><td>
Initializes a new instance of the Unit class.</td></tr></table>&nbsp;
<a href="#unit-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_Unit_Conversions">Conversions</a></td><td>
Gets an array of <a href="T_DevCase_Core_Maths_UnitConversion">UnitConversion</a> containing conversion functions between this Unit and another.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_Unit_Factor">Factor</a></td><td>
Gets the factor of the unit.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_Unit_Name">Name</a></td><td>
Gets the name of the unit.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_Unit_Symbol">Symbol</a></td><td>
Gets the symbol of the unit.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_Unit_UnitType">UnitType</a></td><td>
Gets the type of the unit.</td></tr></table>&nbsp;
<a href="#unit-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified Object is equal to this instance.
 (Overrides AestheticObject.Equals(Object).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit_Equals">Equals(Unit)</a></td><td>
Determines whether the specified Unit is equal to this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides AestheticObject.GetHashCode().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit_IsCompatibleWith">IsCompatibleWith</a></td><td>
Determines whether the specified Unit is compatible with this one.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit_Power">Power</a></td><td>
Raises the current Unit to the specified power. 

 I.e. `Units.Length.Metre.Power(3)` would return a cubic metre unit.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit_ToString">ToString()</a></td><td>
Returns a string representation of this Unit.
 (Overrides AestheticObject.ToString().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit_ToString_1">ToString(IFormatProvider)</a></td><td>
Returns a string representation of this Unit.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit_ToString_2">ToString(String)</a></td><td>
Returns a string representation of this Unit.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Unit_ToString_3">ToString(String, IFormatProvider)</a></td><td>
Returns a string representation of this Unit.</td></tr></table>&nbsp;
<a href="#unit-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Division_2">Division(Double, Unit)</a></td><td>
Implements the operator /</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Division">Division(Unit, Unit)</a></td><td>
Implements the operator /</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Division_1">Division(Unit, Double)</a></td><td>
Implements the operator /</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Equality">Equality</a></td><td>
Implements the operator =</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Exponent_2">Exponent(Double, Unit)</a></td><td>
Implements the operator ^</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Exponent">Exponent(Unit, Unit)</a></td><td>
Implements the operator ^</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Exponent_1">Exponent(Unit, Double)</a></td><td>
Implements the operator ^</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Inequality">Inequality</a></td><td>
Implements the operator <></td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Multiply_2">Multiply(Double, Unit)</a></td><td>
Implements the operator *</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Multiply">Multiply(Unit, Unit)</a></td><td>
Implements the operator *</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Unit_op_Multiply_1">Multiply(Unit, Double)</a></td><td>
Implements the operator *</td></tr></table>&nbsp;
<a href="#unit-class">Back to Top</a>

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
<a href="#unit-class">Back to Top</a>

## Explicit Interface Implementations
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Unit_System_IComparable{DevCase_Core_Maths_Unit}_CompareTo">IComparable(Unit).CompareTo</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Unit_System_IComparable_CompareTo">IComparable.CompareTo</a></td><td /></tr></table>&nbsp;
<a href="#unit-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />