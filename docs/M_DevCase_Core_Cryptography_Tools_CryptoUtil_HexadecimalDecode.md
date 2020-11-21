# CryptoUtil.HexadecimalDecode Method 
 

Decodes a string using Hexadecimal codification.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string HexadecimalDecode(
	string str,
	string separator = "",
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function HexadecimalDecode ( 
	str As String,
	Optional separator As String = "",
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim separator As String
Dim enc As Encoding
Dim returnValue As String

returnValue = CryptoUtil.HexadecimalDecode(str, 
	separator, enc)
```

**C++**<br />
``` C++
public:
static String^ HexadecimalDecode(
	String^ str, 
	String^ separator = L"", 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member HexadecimalDecode : 
        str : string * 
        ?separator : string * 
        ?enc : Encoding 
(* Defaults:
        let _separator = defaultArg separator ""
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to decode.</dd><dt>separator (Optional)</dt><dd>Type: System.String<br />The string used to separate Hexadecimal sequences.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

#### Return Value
Type: String<br />The decoded string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim decoded As String = HexadecimalDecode("48 65 6c 6c 6f 20 57 6f 72 6c 64 21", separator:=" ")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />