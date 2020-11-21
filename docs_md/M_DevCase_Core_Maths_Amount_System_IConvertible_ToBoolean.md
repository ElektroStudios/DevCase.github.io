# Amount.IConvertible.ToBoolean Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
bool IConvertible.ToBoolean(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToBoolean ( 
	provider As IFormatProvider
) As Boolean Implements IConvertible.ToBoolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As Boolean

returnValue = CType(instance, IConvertible).ToBoolean(provider)
```

**C++**<br />
``` C++
private:
virtual bool IConvertible_ToBoolean(
	IFormatProvider^ provider
) sealed = IConvertible::ToBoolean
```

**F#**<br />
``` F#
private abstract IConvertible_ToBoolean : 
        provider : IFormatProvider -> bool 
private override IConvertible_ToBoolean : 
        provider : IFormatProvider -> bool 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToBoolean(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Boolean<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToBoolean(System.IFormatProvider)"\]

#### Implements
IConvertible.ToBoolean(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />