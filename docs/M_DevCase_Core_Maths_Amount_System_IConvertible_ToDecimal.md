# Amount.IConvertible.ToDecimal Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
decimal IConvertible.ToDecimal(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToDecimal ( 
	provider As IFormatProvider
) As Decimal Implements IConvertible.ToDecimal
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As Decimal

returnValue = CType(instance, IConvertible).ToDecimal(provider)
```

**C++**<br />
``` C++
private:
virtual Decimal IConvertible_ToDecimal(
	IFormatProvider^ provider
) sealed = IConvertible::ToDecimal
```

**F#**<br />
``` F#
private abstract IConvertible_ToDecimal : 
        provider : IFormatProvider -> decimal 
private override IConvertible_ToDecimal : 
        provider : IFormatProvider -> decimal 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToDecimal(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Decimal<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToDecimal(System.IFormatProvider)"\]

#### Implements
IConvertible.ToDecimal(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />