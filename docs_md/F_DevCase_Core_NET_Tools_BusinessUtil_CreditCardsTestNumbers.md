# BusinessUtil.CreditCardsTestNumbers Field
 

Contains a collection of credit card numbers for testing purposes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static readonly Dictionary<string, string[]> CreditCardsTestNumbers
```

**VB**<br />
``` VB
Public Shared ReadOnly CreditCardsTestNumbers As Dictionary(Of String, String())
```

**VB Usage**<br />
``` VB Usage
Dim value As Dictionary(Of String, String())

value = BusinessUtil.CreditCardsTestNumbers

```

**C++**<br />
``` C++
public:
static initonly Dictionary<String^, array<String^>^>^ CreditCardsTestNumbers
```

**F#**<br />
``` F#
static val CreditCardsTestNumbers: Dictionary<string, string[]>
```


#### Field Value
Type: Dictionary(String, String[])

## Remarks
<a href="http://www.paypalobjects.com/en_US/vhelp/paypalmanager_help/credit_card_numbers.htm" target="_blank">http://www.paypalobjects.com/en_US/vhelp/paypalmanager_help/credit_card_numbers.htm</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each card As KeyValuePair(Of String, String()) In CreditCardsTestNumbers
    For Each cardnumber As String In card.Value
        Dim isValidNumber As Boolean = BusinessUtil.ValidateCreditCardNumber(cardnumber)
        Console.WriteLine("Card type: '{0}'; Number: '{1}'; Is Valid?: {2}", card.Key, cardnumber, isValidNumber)
    Next cardnumber
Next card
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_BusinessUtil">BusinessUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />