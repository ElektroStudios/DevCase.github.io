# CryptoUtil.Base36Decode Method 
 

Decodes a string using Base36 codification.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static long Base36Decode(
	string str
)
```

**VB**<br />
``` VB
Public Shared Function Base36Decode ( 
	str As String
) As Long
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim returnValue As Long

returnValue = CryptoUtil.Base36Decode(str)
```

**C++**<br />
``` C++
public:
static long long Base36Decode(
	String^ str
)
```

**F#**<br />
``` F#
static member Base36Decode : 
        str : string -> int64 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to decode.</dd></dl>

#### Return Value
Type: Int64<br />The decoded number.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim decoded As String = Base36Decode("KF12OI") ' 1234567890
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />