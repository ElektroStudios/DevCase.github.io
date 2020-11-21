# Amount Class
 

Represents an amount of a <a href="T_DevCase_Core_Maths_Unit">Unit</a>.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Maths.Amount<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
public sealed class Amount : AestheticObject, 
	ICloneable, IComparable, IComparable<Amount>, IConvertible, 
	IEquatable<Amount>, IFormattable
```

**VB**<br />
``` VB
<SerializableAttribute>
Public NotInheritable Class Amount
	Inherits AestheticObject
	Implements ICloneable, IComparable, IComparable(Of Amount), 
	IConvertible, IEquatable(Of Amount), IFormattable
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
```

**C++**<br />
``` C++
[SerializableAttribute]
public ref class Amount sealed : public AestheticObject, 
	ICloneable, IComparable, IComparable<Amount^>, IConvertible, 
	IEquatable<Amount^>, IFormattable
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
type Amount =  
    class
        inherit AestheticObject
        interface ICloneable
        interface IComparable
        interface IComparable<Amount>
        interface IConvertible
        interface IEquatable<Amount>
        interface IFormattable
    end
```

The Amount type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount__ctor">Amount</a></td><td>
Initializes a new instance of the Amount class.</td></tr></table>&nbsp;
<a href="#amount-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Maths_Amount_EqualityPrecision">EqualityPrecision</a></td><td>
Gets or sets a value indicating the decimal precision to which two amounts are considered equal.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_Amount_Unit">Unit</a></td><td>
Gets the <a href="T_DevCase_Core_Maths_Unit">Unit</a> of this amount.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Maths_Amount_Value">Value</a></td><td>
Gets the value of this amount.</td></tr></table>&nbsp;
<a href="#amount-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_Add">Add</a></td><td>
Adds this Amount with the specified Amount (= this + amount).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_Clone">Clone</a></td><td>
Returns a clone of this object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_ConvertedTo">ConvertedTo(Unit)</a></td><td>
Returns an Amount converted to the specified <a href="T_DevCase_Core_Maths_Unit">Unit</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_ConvertedTo_1">ConvertedTo(Unit, Int32)</a></td><td>
Returns an Amount converted to the specified <a href="T_DevCase_Core_Maths_Unit">Unit</a> and rounded up to the given decimal precision.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_DivideBy_1">DivideBy(Double)</a></td><td>
Divides this Amount by the specified value (= this / value).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_DivideBy">DivideBy(Amount)</a></td><td>
Divides this Amount by the specified Amount (= this / amount).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified Object is equal to this instance.
 (Overrides AestheticObject.Equals(Object).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_Equals">Equals(Amount)</a></td><td>
Determines whether the specified Amount is equal to the current one.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides AestheticObject.GetHashCode().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_Inverse">Inverse</a></td><td>
Returns 1 over this Amount (= 1 / this).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_Multiply_1">Multiply(Double)</a></td><td>
Multiply this Amount with the specified value (= this * value).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_Multiply">Multiply(Amount)</a></td><td>
Multiplies this Amount with the specified Amount (= this * amount).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_Negate">Negate</a></td><td>
Negates this Amount (= -this).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_Power">Power</a></td><td>
Raises this Amount to the specified power.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_ToString">ToString()</a></td><td>
Returns a String that represents this Amount.
 (Overrides AestheticObject.ToString().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_ToString_5">ToString(IFormatProvider)</a></td><td>
Returns a String that represents this Amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_ToString_6">ToString(String)</a></td><td>
Returns a String that represents this Amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_ToString_1">ToString(Amount)</a></td><td>
Returns a String that represents an Amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Maths_Amount_ToString_7">ToString(String, IFormatProvider)</a></td><td>
Returns a String that represents this Amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_ToString_2">ToString(Amount, IFormatProvider)</a></td><td>
Returns a String that represents an Amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_ToString_3">ToString(Amount, String)</a></td><td>
Returns a String that represents an Amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_ToString_4">ToString(Amount, String, IFormatProvider)</a></td><td>
Returns a String that represents an Amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_Zero">Zero</a></td><td>
Zeroes the specified <a href="T_DevCase_Core_Maths_Unit">Unit</a>.</td></tr></table>&nbsp;
<a href="#amount-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Addition">Addition</a></td><td>
Sums two Amount of compatible units.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Division_2">Division(Double, Amount)</a></td><td>
Divides a Double value by an Amount.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Division">Division(Amount, Amount)</a></td><td>
Divides two Amount.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Division_1">Division(Amount, Double)</a></td><td>
Divides an Amount by a Double value.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Equality">Equality</a></td><td>
Compares two Amount.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Explicit">Explicit(Amount to Nullable(Double))</a></td><td>
Casts an Amount to a double.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_GreaterThan">GreaterThan</a></td><td>
Compares two Amount of compatible units.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_GreaterThanOrEqual">GreaterThanOrEqual</a></td><td>
Compares two Amount of compatible units.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Inequality">Inequality</a></td><td>
Compares two Amount.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_LessThan">LessThan</a></td><td>
Compares two Amount of compatible units.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_LessThanOrEqual">LessThanOrEqual</a></td><td>
Compares two Amount of compatible units.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Multiply_2">Multiply(Double, Amount)</a></td><td>
Multiplies a Double value with an Amount.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Multiply">Multiply(Amount, Amount)</a></td><td>
Multiplies two Amount.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Multiply_1">Multiply(Amount, Double)</a></td><td>
Multiplies an Amount with a Double value.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_Subtraction">Subtraction</a></td><td>
Substracts two Amount of compatible units.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_UnaryNegation">UnaryNegation</a></td><td>
Substracts an Amount.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Maths_Amount_op_UnaryPlus">UnaryPlus</a></td><td>
Sums an Amount.</td></tr></table>&nbsp;
<a href="#amount-class">Back to Top</a>

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
<a href="#amount-class">Back to Top</a>

## Explicit Interface Implementations
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IComparable{DevCase_Core_Maths_Amount}_CompareTo">IComparable(Amount).CompareTo</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IComparable_CompareTo">IComparable.CompareTo</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_GetTypeCode">IConvertible.GetTypeCode</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToBoolean">IConvertible.ToBoolean</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToByte">IConvertible.ToByte</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToChar">IConvertible.ToChar</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToDateTime">IConvertible.ToDateTime</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToDecimal">IConvertible.ToDecimal</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToDouble">IConvertible.ToDouble</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToInt16">IConvertible.ToInt16</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToInt32">IConvertible.ToInt32</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToInt64">IConvertible.ToInt64</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToSByte">IConvertible.ToSByte</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToSingle">IConvertible.ToSingle</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToString">IConvertible.ToString</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToType">IConvertible.ToType</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToUInt16">IConvertible.ToUInt16</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToUInt32">IConvertible.ToUInt32</a></td><td /></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Maths_Amount_System_IConvertible_ToUInt64">IConvertible.ToUInt64</a></td><td /></tr></table>&nbsp;
<a href="#amount-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim b1 As New Amount(1, Units.DigitalInformation.Byte)
Dim kb1 As New Amount(1, Units.DigitalInformation.Kilobyte)
Dim mb1 As New Amount(1, Units.DigitalInformation.Megabyte)

Dim sb As New Global.System.Text.StringBuilder()
With sb
    .AppendLine(String.Format("{0} bytes is equal to {1} bits", b1.Value, b1.ConvertedTo(Units.DigitalInformation.Bit).Value))
    .AppendLine(String.Format("{0} bytes is equal to {1} bytes", b1.Value, b1.ConvertedTo(Units.DigitalInformation.Byte).Value))

    .AppendLine(String.Format("{0} kilobytes is equal to {1} bits", kb1.Value, kb1.ConvertedTo(Units.DigitalInformation.Bit).Value))
    .AppendLine(String.Format("{0} kilobytes is equal to {1} bytes", kb1.Value, kb1.ConvertedTo(Units.DigitalInformation.Byte).Value))
    .AppendLine(String.Format("{0} kilobytes is equal to {1} kilobits", kb1.Value, kb1.ConvertedTo(Units.DigitalInformation.Kilobit).Value))
    .AppendLine(String.Format("{0} kilobytes is equal to {1} kilobytes", kb1.Value, kb1.ConvertedTo(Units.DigitalInformation.Kilobyte).Value))

    .AppendLine(String.Format("{0} megabytes is equal to {1} bits", mb1.Value, mb1.ConvertedTo(Units.DigitalInformation.Bit).Value))
    .AppendLine(String.Format("{0} megabytes is equal to {1} bytes", mb1.Value, mb1.ConvertedTo(Units.DigitalInformation.Byte).Value))
    .AppendLine(String.Format("{0} megabytes is equal to {1} kilobits", mb1.Value, mb1.ConvertedTo(Units.DigitalInformation.Kilobit).Value))
    .AppendLine(String.Format("{0} megabytes is equal to {1} Kilobytes", mb1.Value, mb1.ConvertedTo(Units.DigitalInformation.Kilobyte).Value))
    .AppendLine(String.Format("{0} megabytes is equal to {1} megabits", mb1.Value, mb1.ConvertedTo(Units.DigitalInformation.Megabit).Value))
    .AppendLine(String.Format("{0} megabytes is equal to {1} megabytes", mb1.Value, mb1.ConvertedTo(Units.DigitalInformation.Megabyte).Value))
End With

Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />