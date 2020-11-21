# Amount.IConvertible.ToSByte Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
sbyte IConvertible.ToSByte(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToSByte ( 
	provider As IFormatProvider
) As SByte Implements IConvertible.ToSByte
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As SByte

returnValue = CType(instance, IConvertible).ToSByte(provider)
```

**C++**<br />
``` C++
private:
virtual signed char IConvertible_ToSByte(
	IFormatProvider^ provider
) sealed = IConvertible::ToSByte
```

**F#**<br />
``` F#
private abstract IConvertible_ToSByte : 
        provider : IFormatProvider -> sbyte 
private override IConvertible_ToSByte : 
        provider : IFormatProvider -> sbyte 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToSByte(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: SByte<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToSByte(System.IFormatProvider)"\]

#### Implements
IConvertible.ToSByte(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />