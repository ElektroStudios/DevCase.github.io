# Amount.IConvertible.ToInt16 Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
short IConvertible.ToInt16(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToInt16 ( 
	provider As IFormatProvider
) As Short Implements IConvertible.ToInt16
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As Short

returnValue = CType(instance, IConvertible).ToInt16(provider)
```

**C++**<br />
``` C++
private:
virtual short IConvertible_ToInt16(
	IFormatProvider^ provider
) sealed = IConvertible::ToInt16
```

**F#**<br />
``` F#
private abstract IConvertible_ToInt16 : 
        provider : IFormatProvider -> int16 
private override IConvertible_ToInt16 : 
        provider : IFormatProvider -> int16 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToInt16(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Int16<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToInt16(System.IFormatProvider)"\]

#### Implements
IConvertible.ToInt16(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />