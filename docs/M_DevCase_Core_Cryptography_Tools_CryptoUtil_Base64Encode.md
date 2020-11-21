# CryptoUtil.Base64Encode Method 
 

Encodes a string using Base64 codification.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Base64Encode(
	string str,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function Base64Encode ( 
	str As String,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim enc As Encoding
Dim returnValue As String

returnValue = CryptoUtil.Base64Encode(str, 
	enc)
```

**C++**<br />
``` C++
public:
static String^ Base64Encode(
	String^ str, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Base64Encode : 
        str : string * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to encode.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

#### Return Value
Type: String<br />The encoded string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim encoded As String = Base64Encode("Hello World!")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />