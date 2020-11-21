# Amount.IConvertible.ToDateTime Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
DateTimeIConvertible.ToDateTime(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToDateTime ( 
	provider As IFormatProvider
) As DateTime Implements IConvertible.ToDateTime
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As DateTime

returnValue = CType(instance, IConvertible).ToDateTime(provider)
```

**C++**<br />
``` C++
private:
virtual DateTime IConvertible_ToDateTime(
	IFormatProvider^ provider
) sealed = IConvertible::ToDateTime
```

**F#**<br />
``` F#
private abstract IConvertible_ToDateTime : 
        provider : IFormatProvider -> DateTime 
private override IConvertible_ToDateTime : 
        provider : IFormatProvider -> DateTime 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToDateTime(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: DateTime<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToDateTime(System.IFormatProvider)"\]

#### Implements
IConvertible.ToDateTime(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />