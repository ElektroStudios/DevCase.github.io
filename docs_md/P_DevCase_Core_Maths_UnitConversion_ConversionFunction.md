# UnitConversion.ConversionFunction Property 
 

Gets the conversion function used to convert the <a href="T_DevCase_Core_Maths_Amount">Amount</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Func<Amount, Amount> ConversionFunction { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ConversionFunction As Func(Of Amount, Amount)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As UnitConversion
Dim value As Func(Of Amount, Amount)

value = instance.ConversionFunction

```

**C++**<br />
``` C++
public:
property Func<Amount^, Amount^>^ ConversionFunction {
	Func<Amount^, Amount^>^ get ();
}
```

**F#**<br />
``` F#
member ConversionFunction : Func<Amount, Amount> with get

```


#### Property Value
Type: Func(<a href="T_DevCase_Core_Maths_Amount">Amount</a>, <a href="T_DevCase_Core_Maths_Amount">Amount</a>)<br />The conversion function used to convert the <a href="T_DevCase_Core_Maths_Amount">Amount</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_UnitConversion">UnitConversion Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />