# BusinessUtil.ValidateCreditCardNumber Method 
 

Uses the Luhn algorithm to determines whether the specified credit card number is valid. 

 Please de aware that not all valid credit cards can be verified with the Luhn algorithm because it not covers all range of card numbers, however the Luhn algorithm does work for many, if not most, major credit cards. 

 The Luhn algorithm is simply used to prevent transpositional errors, it is useful as a sanity check prior to submitting card numbers to a payment gateway, but not suitable to absolutely validate whether a number is a valid card number. 

 The only way to absolutely verify a credit card number is to validate it via a payment gateway.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ValidateCreditCardNumber(
	string cardNumber
)
```

**VB**<br />
``` VB
Public Shared Function ValidateCreditCardNumber ( 
	cardNumber As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim cardNumber As String
Dim returnValue As Boolean

returnValue = BusinessUtil.ValidateCreditCardNumber(cardNumber)
```

**C++**<br />
``` C++
public:
static bool ValidateCreditCardNumber(
	String^ cardNumber
)
```

**F#**<br />
``` F#
static member ValidateCreditCardNumber : 
        cardNumber : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>cardNumber</dt><dd>Type: System.String<br />The credit card number.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified card number is a valid card number; otherwise, `false` (`False` in Visual Basic).

## Remarks
Luhn algorithm: <a href="http://en.wikipedia.org/wiki/Luhn_algorithm" target="_blank">http://en.wikipedia.org/wiki/Luhn_algorithm</a>

 Microsoft's Luhn algorithm implementation: <a href="http://referencesource.microsoft.com/#System.ComponentModel.DataAnnotations/DataAnnotations/CreditCardAttribute.cs" target="_blank">http://referencesource.microsoft.com/#System.ComponentModel.DataAnnotations/DataAnnotations/CreditCardAttribute.cs</a>

 Credits to: <a href="http://www.vcskicks.com/credit-card-verification.php" target="_blank">http://www.vcskicks.com/credit-card-verification.php</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim visaNumber As String = "4012888888881881"
Dim isValid As Boolean = ValidateCreditCardNumber(visaNumber)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_BusinessUtil">BusinessUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />