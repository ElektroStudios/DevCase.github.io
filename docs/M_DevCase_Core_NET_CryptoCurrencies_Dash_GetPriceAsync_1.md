# Dash.GetPriceAsync Method (Double, Currencies)
 

Asynchronously gets the price for the specified amount of Dashes converted to the specified currency.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Task<double> GetPriceAsync(
	double amount,
	Currencies currency
)
```

**VB**<br />
``` VB
Public Overridable Function GetPriceAsync ( 
	amount As Double,
	currency As Currencies
) As Task(Of Double)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Dash
Dim amount As Double
Dim currency As Currencies
Dim returnValue As Task(Of Double)

returnValue = instance.GetPriceAsync(amount, 
	currency)
```

**C++**<br />
``` C++
public:
virtual Task<double>^ GetPriceAsync(
	double amount, 
	Currencies currency
)
```

**F#**<br />
``` F#
abstract GetPriceAsync : 
        amount : float * 
        currency : Currencies -> Task<float> 
override GetPriceAsync : 
        amount : float * 
        currency : Currencies -> Task<float> 
```


#### Parameters
&nbsp;<dl><dt>amount</dt><dd>Type: System.Double<br />The amount of Dashes. (eg. '0.5', '1', or "1.5" )</dd><dt>currency</dt><dd>Type: <a href="T_DevCase_Core_NET_Currencies">DevCase.Core.NET.Currencies</a><br />The target currency.</dd></dl>

#### Return Value
Type: Task(Double)<br />The resulting price for the specified amount of Dashes converted to the specified currency.

#### Implements
<a href="M_DevCase_Core_NET_ICryptoCurrency_GetPriceAsync_1">ICryptoCurrency.GetPriceAsync(Double, Currencies)</a><br />

## See Also


#### Reference
<a href="T_DevCase_Core_NET_CryptoCurrencies_Dash">Dash Class</a><br /><a href="Overload_DevCase_Core_NET_CryptoCurrencies_Dash_GetPriceAsync">GetPriceAsync Overload</a><br /><a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies Namespace</a><br />