# CryptoUtil.CaesarEncrypt Method 
 

Encrypts a string using Caesar's substitution cipher.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string CaesarEncrypt(
	string text,
	int positions,
	string charSet = ""
)
```

**VB**<br />
``` VB
Public Shared Function CaesarEncrypt ( 
	text As String,
	positions As Integer,
	Optional charSet As String = ""
) As String
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim positions As Integer
Dim charSet As String
Dim returnValue As String

returnValue = CryptoUtil.CaesarEncrypt(text, 
	positions, charSet)
```

**C++**<br />
``` C++
public:
static String^ CaesarEncrypt(
	String^ text, 
	int positions, 
	String^ charSet = L""
)
```

**F#**<br />
``` F#
static member CaesarEncrypt : 
        text : string * 
        positions : int * 
        ?charSet : string 
(* Defaults:
        let _charSet = defaultArg charSet ""
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to encrypt.</dd><dt>positions</dt><dd>Type: System.Int32<br />The character position shifting.</dd><dt>charSet (Optional)</dt><dd>Type: System.String<br />A set of characters to use in encoding.</dd></dl>

#### Return Value
Type: String<br />The encrypted string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim encrypted As String = CaesarEncrypt("Hello World!", positions:=15)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />