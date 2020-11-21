# CryptoUtil.GetRandomNumericPassword Method 
 

Generates a random numeric password of the specified amount of secuences delimited by a separator.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetRandomNumericPassword(
	int secuences,
	int length,
	string separator
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomNumericPassword ( 
	secuences As Integer,
	length As Integer,
	separator As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim secuences As Integer
Dim length As Integer
Dim separator As String
Dim returnValue As String

returnValue = CryptoUtil.GetRandomNumericPassword(secuences, 
	length, separator)
```

**C++**<br />
``` C++
public:
static String^ GetRandomNumericPassword(
	int secuences, 
	int length, 
	String^ separator
)
```

**F#**<br />
``` F#
static member GetRandomNumericPassword : 
        secuences : int * 
        length : int * 
        separator : string -> string 

```


#### Parameters
&nbsp;<dl><dt>secuences</dt><dd>Type: System.Int32<br />The amount of secuences.</dd><dt>length</dt><dd>Type: System.Int32<br />The secuence length.</dd><dt>separator</dt><dd>Type: System.String<br />The string used to separate the secuences.</dd></dl>

#### Return Value
Type: String<br />The resulting password.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Positive value is required.;secuences or Positive value is required.;length</td></tr><tr><td>ArgumentNullException</td><td>separator</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pass As String = GetRandomNumericPassword(secuences:=4, length:=5, separator:="-")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />