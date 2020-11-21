# Amount.IConvertible.ToUInt16 Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
ushort IConvertible.ToUInt16(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToUInt16 ( 
	provider As IFormatProvider
) As UShort Implements IConvertible.ToUInt16
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As UShort

returnValue = CType(instance, IConvertible).ToUInt16(provider)
```

**C++**<br />
``` C++
private:
virtual unsigned short IConvertible_ToUInt16(
	IFormatProvider^ provider
) sealed = IConvertible::ToUInt16
```

**F#**<br />
``` F#
private abstract IConvertible_ToUInt16 : 
        provider : IFormatProvider -> uint16 
private override IConvertible_ToUInt16 : 
        provider : IFormatProvider -> uint16 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToUInt16(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: UInt16<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToUInt16(System.IFormatProvider)"\]

#### Implements
IConvertible.ToUInt16(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />