# Ethereum.GetPriceAsync Method (Currencies)
 

Asynchronously gets the price for 1 Ethereums converted to the specified currency.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Task<double> GetPriceAsync(
	Currencies currency
)
```

**VB**<br />
``` VB
Public Overridable Function GetPriceAsync ( 
	currency As Currencies
) As Task(Of Double)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Ethereum
Dim currency As Currencies
Dim returnValue As Task(Of Double)

returnValue = instance.GetPriceAsync(currency)
```

**C++**<br />
``` C++
public:
virtual Task<double>^ GetPriceAsync(
	Currencies currency
)
```

**F#**<br />
``` F#
abstract GetPriceAsync : 
        currency : Currencies -> Task<float> 
override GetPriceAsync : 
        currency : Currencies -> Task<float> 
```


#### Parameters
&nbsp;<dl><dt>currency</dt><dd>Type: <a href="T_DevCase_Core_NET_Currencies">DevCase.Core.NET.Currencies</a><br />The target currency.</dd></dl>

#### Return Value
Type: Task(Double)<br />The resulting price for 1 Ethereums converted to the specified currency.

#### Implements
<a href="M_DevCase_Core_NET_ICryptoCurrency_GetPriceAsync">ICryptoCurrency.GetPriceAsync(Currencies)</a><br />

## See Also


#### Reference
<a href="T_DevCase_Core_NET_CryptoCurrencies_Ethereum">Ethereum Class</a><br /><a href="Overload_DevCase_Core_NET_CryptoCurrencies_Ethereum_GetPriceAsync">GetPriceAsync Overload</a><br /><a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies Namespace</a><br />