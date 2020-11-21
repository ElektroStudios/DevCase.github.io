# CryptoUtil.GetRandomHex Method 
 

Generates a random hexadecimal string of the specified lenth.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetRandomHex(
	int length
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomHex ( 
	length As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim length As Integer
Dim returnValue As String

returnValue = CryptoUtil.GetRandomHex(length)
```

**C++**<br />
``` C++
public:
static String^ GetRandomHex(
	int length
)
```

**F#**<br />
``` F#
static member GetRandomHex : 
        length : int -> string 

```


#### Parameters
&nbsp;<dl><dt>length</dt><dd>Type: System.Int32<br />The string length.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Positive value is required.;length</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As String = GetRandomHex(length:=5)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />