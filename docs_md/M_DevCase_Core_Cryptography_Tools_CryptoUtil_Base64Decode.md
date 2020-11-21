# CryptoUtil.Base64Decode Method 
 

Decodes a string using Base64 codification.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Base64Decode(
	string str,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function Base64Decode ( 
	str As String,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim enc As Encoding
Dim returnValue As String

returnValue = CryptoUtil.Base64Decode(str, 
	enc)
```

**C++**<br />
``` C++
public:
static String^ Base64Decode(
	String^ str, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Base64Decode : 
        str : string * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to decode.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

#### Return Value
Type: String<br />The decoded string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim decoded As String = Base64Decode("SGVsbG8gV29ybGQh")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />