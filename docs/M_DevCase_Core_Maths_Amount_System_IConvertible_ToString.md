# Amount.IConvertible.ToString Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
string IConvertible.ToString(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToString ( 
	provider As IFormatProvider
) As String Implements IConvertible.ToString
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As String

returnValue = CType(instance, IConvertible).ToString(provider)
```

**C++**<br />
``` C++
private:
virtual String^ IConvertible_ToString(
	IFormatProvider^ provider
) sealed = IConvertible::ToString
```

**F#**<br />
``` F#
private abstract IConvertible_ToString : 
        provider : IFormatProvider -> string 
private override IConvertible_ToString : 
        provider : IFormatProvider -> string 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToString(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToString(System.IFormatProvider)"\]

#### Implements
IConvertible.ToString(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />