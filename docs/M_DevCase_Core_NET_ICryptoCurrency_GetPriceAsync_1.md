# ICryptoCurrency.GetPriceAsync Method (Double, Currencies)
 

Asynchronously gets the price equivalency for the specified amount of this <a href="T_DevCase_Core_NET_ICryptoCurrency">ICryptoCurrency</a> converted to the specified currency.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
Task<double> GetPriceAsync(
	double amount,
	Currencies currency
)
```

**VB**<br />
``` VB
Function GetPriceAsync ( 
	amount As Double,
	currency As Currencies
) As Task(Of Double)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ICryptoCurrency
Dim amount As Double
Dim currency As Currencies
Dim returnValue As Task(Of Double)

returnValue = instance.GetPriceAsync(amount, 
	currency)
```

**C++**<br />
``` C++
Task<double>^ GetPriceAsync(
	double amount, 
	Currencies currency
)
```

**F#**<br />
``` F#
abstract GetPriceAsync : 
        amount : float * 
        currency : Currencies -> Task<float> 

```


#### Parameters
&nbsp;<dl><dt>amount</dt><dd>Type: System.Double<br />The amount of this <a href="T_DevCase_Core_NET_ICryptoCurrency">ICryptoCurrency</a>.</dd><dt>currency</dt><dd>Type: <a href="T_DevCase_Core_NET_Currencies">DevCase.Core.NET.Currencies</a><br />The target currency.</dd></dl>

#### Return Value
Type: Task(Double)<br />The resulting price for the specified amount of this <a href="T_DevCase_Core_NET_ICryptoCurrency">ICryptoCurrency</a> converted to the specified currency.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_ICryptoCurrency">ICryptoCurrency Interface</a><br /><a href="Overload_DevCase_Core_NET_ICryptoCurrency_GetPriceAsync">GetPriceAsync Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />