# Cardano.GetPrice Method (Double, Currencies)
 

Gets the price for the specified amount of Cardans converted to the specified currency.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual double GetPrice(
	double amount,
	Currencies currency
)
```

**VB**<br />
``` VB
Public Overridable Function GetPrice ( 
	amount As Double,
	currency As Currencies
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim instance As Cardano
Dim amount As Double
Dim currency As Currencies
Dim returnValue As Double

returnValue = instance.GetPrice(amount, 
	currency)
```

**C++**<br />
``` C++
public:
virtual double GetPrice(
	double amount, 
	Currencies currency
)
```

**F#**<br />
``` F#
abstract GetPrice : 
        amount : float * 
        currency : Currencies -> float 
override GetPrice : 
        amount : float * 
        currency : Currencies -> float 
```


#### Parameters
&nbsp;<dl><dt>amount</dt><dd>Type: System.Double<br />The amount of Cardans. (eg. '0.5', '1', or "1.5" )</dd><dt>currency</dt><dd>Type: <a href="T_DevCase_Core_NET_Currencies">DevCase.Core.NET.Currencies</a><br />The target currency.</dd></dl>

#### Return Value
Type: Double<br />The resulting price for the specified amount of Cardans converted to the specified currency.

#### Implements
<a href="M_DevCase_Core_NET_ICryptoCurrency_GetPrice_1">ICryptoCurrency.GetPrice(Double, Currencies)</a><br />

## See Also


#### Reference
<a href="T_DevCase_Core_NET_CryptoCurrencies_Cardano">Cardano Class</a><br /><a href="Overload_DevCase_Core_NET_CryptoCurrencies_Cardano_GetPrice">GetPrice Overload</a><br /><a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies Namespace</a><br />