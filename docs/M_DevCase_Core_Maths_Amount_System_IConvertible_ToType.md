# Amount.IConvertible.ToType Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
ObjectIConvertible.ToType(
	Type conversionType,
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToType ( 
	conversionType As Type,
	provider As IFormatProvider
) As Object Implements IConvertible.ToType
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim conversionType As Type
Dim provider As IFormatProvider
Dim returnValue As Object

returnValue = CType(instance, IConvertible).ToType(conversionType, 
	provider)
```

**C++**<br />
``` C++
private:
virtual Object^ IConvertible_ToType(
	Type^ conversionType, 
	IFormatProvider^ provider
) sealed = IConvertible::ToType
```

**F#**<br />
``` F#
private abstract IConvertible_ToType : 
        conversionType : Type * 
        provider : IFormatProvider -> Object 
private override IConvertible_ToType : 
        conversionType : Type * 
        provider : IFormatProvider -> Object 
```


#### Parameters
&nbsp;<dl><dt>conversionType</dt><dd>Type: System.Type<br />\[Missing <param name="conversionType"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToType(System.Type,System.IFormatProvider)"\]</dd><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToType(System.Type,System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Object<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToType(System.Type,System.IFormatProvider)"\]

#### Implements
IConvertible.ToType(Type, IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />