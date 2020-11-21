# CryptoUtil.BinaryDecode Method 
 

Decodes a string using Binary codification.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string BinaryDecode(
	string str,
	string separator = "",
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function BinaryDecode ( 
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

returnValue = CryptoUtil.BinaryDecode(str, 
	separator, enc)
```

**C++**<br />
``` C++
public:
static String^ BinaryDecode(
	String^ str, 
	String^ separator = L"", 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member BinaryDecode : 
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
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to decode.</dd><dt>separator (Optional)</dt><dd>Type: System.String<br />\[Missing <param name="separator"/> documentation for "M:DevCase.Core.Cryptography.Tools.CryptoUtil.BinaryDecode(System.String,System.String,System.Text.Encoding)"\]</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

#### Return Value
Type: String<br />The decoded string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim decoded As String = BinaryDecode("01001000 01100101 01101100 01101100 01101111 00100000 01010111 01101111 01110010 01101100 01100100 00100001", separator:=" ")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />