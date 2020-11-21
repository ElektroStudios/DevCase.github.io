# Amount.IConvertible.ToInt64 Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
long IConvertible.ToInt64(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToInt64 ( 
	provider As IFormatProvider
) As Long Implements IConvertible.ToInt64
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As Long

returnValue = CType(instance, IConvertible).ToInt64(provider)
```

**C++**<br />
``` C++
private:
virtual long long IConvertible_ToInt64(
	IFormatProvider^ provider
) sealed = IConvertible::ToInt64
```

**F#**<br />
``` F#
private abstract IConvertible_ToInt64 : 
        provider : IFormatProvider -> int64 
private override IConvertible_ToInt64 : 
        provider : IFormatProvider -> int64 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToInt64(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Int64<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToInt64(System.IFormatProvider)"\]

#### Implements
IConvertible.ToInt64(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />