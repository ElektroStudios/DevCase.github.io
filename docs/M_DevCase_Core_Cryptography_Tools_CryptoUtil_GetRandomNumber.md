# CryptoUtil.GetRandomNumber Method 
 

Generates a random numeric value of the specified lenth.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetRandomNumber(
	int length
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomNumber ( 
	length As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim length As Integer
Dim returnValue As String

returnValue = CryptoUtil.GetRandomNumber(length)
```

**C++**<br />
``` C++
public:
static String^ GetRandomNumber(
	int length
)
```

**F#**<br />
``` F#
static member GetRandomNumber : 
        length : int -> string 

```


#### Parameters
&nbsp;<dl><dt>length</dt><dd>Type: System.Int32<br />The number length.</dd></dl>

#### Return Value
Type: String<br />The resulting numeric value.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Positive value is required.;length</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As String = GetRandomNumber(length:=5)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />