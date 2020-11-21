# Amount.IConvertible.ToDouble Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
double IConvertible.ToDouble(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToDouble ( 
	provider As IFormatProvider
) As Double Implements IConvertible.ToDouble
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As Double

returnValue = CType(instance, IConvertible).ToDouble(provider)
```

**C++**<br />
``` C++
private:
virtual double IConvertible_ToDouble(
	IFormatProvider^ provider
) sealed = IConvertible::ToDouble
```

**F#**<br />
``` F#
private abstract IConvertible_ToDouble : 
        provider : IFormatProvider -> float 
private override IConvertible_ToDouble : 
        provider : IFormatProvider -> float 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToDouble(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Double<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToDouble(System.IFormatProvider)"\]

#### Implements
IConvertible.ToDouble(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />