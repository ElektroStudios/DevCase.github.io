# Amount.IConvertible.ToByte Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
byte IConvertible.ToByte(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToByte ( 
	provider As IFormatProvider
) As Byte Implements IConvertible.ToByte
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As Byte

returnValue = CType(instance, IConvertible).ToByte(provider)
```

**C++**<br />
``` C++
private:
virtual unsigned char IConvertible_ToByte(
	IFormatProvider^ provider
) sealed = IConvertible::ToByte
```

**F#**<br />
``` F#
private abstract IConvertible_ToByte : 
        provider : IFormatProvider -> byte 
private override IConvertible_ToByte : 
        provider : IFormatProvider -> byte 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToByte(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Byte<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToByte(System.IFormatProvider)"\]

#### Implements
IConvertible.ToByte(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />