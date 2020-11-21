# Amount.IConvertible.ToSingle Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
float IConvertible.ToSingle(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToSingle ( 
	provider As IFormatProvider
) As Single Implements IConvertible.ToSingle
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As Single

returnValue = CType(instance, IConvertible).ToSingle(provider)
```

**C++**<br />
``` C++
private:
virtual float IConvertible_ToSingle(
	IFormatProvider^ provider
) sealed = IConvertible::ToSingle
```

**F#**<br />
``` F#
private abstract IConvertible_ToSingle : 
        provider : IFormatProvider -> float32 
private override IConvertible_ToSingle : 
        provider : IFormatProvider -> float32 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToSingle(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Single<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToSingle(System.IFormatProvider)"\]

#### Implements
IConvertible.ToSingle(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />