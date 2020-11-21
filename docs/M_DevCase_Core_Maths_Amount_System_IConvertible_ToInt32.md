# Amount.IConvertible.ToInt32 Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
int IConvertible.ToInt32(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToInt32 ( 
	provider As IFormatProvider
) As Integer Implements IConvertible.ToInt32
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As Integer

returnValue = CType(instance, IConvertible).ToInt32(provider)
```

**C++**<br />
``` C++
private:
virtual int IConvertible_ToInt32(
	IFormatProvider^ provider
) sealed = IConvertible::ToInt32
```

**F#**<br />
``` F#
private abstract IConvertible_ToInt32 : 
        provider : IFormatProvider -> int 
private override IConvertible_ToInt32 : 
        provider : IFormatProvider -> int 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToInt32(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Int32<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToInt32(System.IFormatProvider)"\]

#### Implements
IConvertible.ToInt32(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />