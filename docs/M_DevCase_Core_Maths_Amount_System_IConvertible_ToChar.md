# Amount.IConvertible.ToChar Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
char IConvertible.ToChar(
	IFormatProvider provider
)
```

**VB**<br />
``` VB
Private Function IConvertible_ToChar ( 
	provider As IFormatProvider
) As Char Implements IConvertible.ToChar
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim provider As IFormatProvider
Dim returnValue As Char

returnValue = CType(instance, IConvertible).ToChar(provider)
```

**C++**<br />
``` C++
private:
virtual wchar_t IConvertible_ToChar(
	IFormatProvider^ provider
) sealed = IConvertible::ToChar
```

**F#**<br />
``` F#
private abstract IConvertible_ToChar : 
        provider : IFormatProvider -> char 
private override IConvertible_ToChar : 
        provider : IFormatProvider -> char 
```


#### Parameters
&nbsp;<dl><dt>provider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="provider"/> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToChar(System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: Char<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#ToChar(System.IFormatProvider)"\]

#### Implements
IConvertible.ToChar(IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />