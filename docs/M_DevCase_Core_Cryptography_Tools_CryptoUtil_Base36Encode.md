# CryptoUtil.Base36Encode Method 
 

Encodes a number using Base36 codification.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Base36Encode(
	long value
)
```

**VB**<br />
``` VB
Public Shared Function Base36Encode ( 
	value As Long
) As String
```

**VB Usage**<br />
``` VB Usage
Dim value As Long
Dim returnValue As String

returnValue = CryptoUtil.Base36Encode(value)
```

**C++**<br />
``` C++
public:
static String^ Base36Encode(
	long long value
)
```

**F#**<br />
``` F#
static member Base36Encode : 
        value : int64 -> string 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.Int64<br />The number to encode.</dd></dl>

#### Return Value
Type: String<br />The encoded string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim encoded As String = Base36Encode(1234567890) ' KF12OI
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />