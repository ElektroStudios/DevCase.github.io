# Dash.GetPrice Method (Currencies)
 

Gets the price for 1 Dashes converted to the specified currency.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual double GetPrice(
	Currencies currency
)
```

**VB**<br />
``` VB
Public Overridable Function GetPrice ( 
	currency As Currencies
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim instance As Dash
Dim currency As Currencies
Dim returnValue As Double

returnValue = instance.GetPrice(currency)
```

**C++**<br />
``` C++
public:
virtual double GetPrice(
	Currencies currency
)
```

**F#**<br />
``` F#
abstract GetPrice : 
        currency : Currencies -> float 
override GetPrice : 
        currency : Currencies -> float 
```


#### Parameters
&nbsp;<dl><dt>currency</dt><dd>Type: <a href="T_DevCase_Core_NET_Currencies">DevCase.Core.NET.Currencies</a><br />The target currency.</dd></dl>

#### Return Value
Type: Double<br />The resulting price for 1 Dashes converted to the specified currency.

#### Implements
<a href="M_DevCase_Core_NET_ICryptoCurrency_GetPrice">ICryptoCurrency.GetPrice(Currencies)</a><br />

## See Also


#### Reference
<a href="T_DevCase_Core_NET_CryptoCurrencies_Dash">Dash Class</a><br /><a href="Overload_DevCase_Core_NET_CryptoCurrencies_Dash_GetPrice">GetPrice Overload</a><br /><a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies Namespace</a><br />