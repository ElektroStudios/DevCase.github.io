# CryptocurrencyUtil.GetCryptoCurrencyPrice Method 
 

Gets the price of the specified cryptocurrency converted to the target currency.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double GetCryptoCurrencyPrice(
	ICryptoCurrency cryptoCurrency,
	double amount,
	Currencies currency
)
```

**VB**<br />
``` VB
Public Shared Function GetCryptoCurrencyPrice ( 
	cryptoCurrency As ICryptoCurrency,
	amount As Double,
	currency As Currencies
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim cryptoCurrency As ICryptoCurrency
Dim amount As Double
Dim currency As Currencies
Dim returnValue As Double

returnValue = CryptocurrencyUtil.GetCryptoCurrencyPrice(cryptoCurrency, 
	amount, currency)
```

**C++**<br />
``` C++
public:
static double GetCryptoCurrencyPrice(
	ICryptoCurrency^ cryptoCurrency, 
	double amount, 
	Currencies currency
)
```

**F#**<br />
``` F#
static member GetCryptoCurrencyPrice : 
        cryptoCurrency : ICryptoCurrency * 
        amount : float * 
        currency : Currencies -> float 

```


#### Parameters
&nbsp;<dl><dt>cryptoCurrency</dt><dd>Type: <a href="T_DevCase_Core_NET_ICryptoCurrency">DevCase.Core.NET.ICryptoCurrency</a><br />The source <a href="T_DevCase_Core_NET_ICryptoCurrency">ICryptoCurrency</a>.</dd><dt>amount</dt><dd>Type: System.Double<br />The amount value of the source cryptocurrency.</dd><dt>currency</dt><dd>Type: <a href="T_DevCase_Core_NET_Currencies">DevCase.Core.NET.Currencies</a><br />The target currency.</dd></dl>

#### Return Value
Type: Double<br />The resulting price.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NotImplementedException</td><td>The specified currency is not supported by this API.</td></tr><tr><td>HttpListenerException</td><td>The requested cryptocurrency rate info is empty due to an unknown error.</td></tr><tr><td>FormatException</td><td>Element name '{0}' not found. Unknown error reason.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim btc As ICryptoCurrency = New Bitcoin()
Dim price As double = GetCryptoCurrencyPrice(btc, 1, Currencies.USD)
Console.WriteLine(String.Format("{0:C}", price, CultureInfo.GetCultureInfo("en-US")))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_CryptocurrencyUtil">CryptocurrencyUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />