# CryptoUtil.XorEncryptOrDecrypt Method 
 

Encrypts or decrypts a string using XOR algorithm.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string XorEncryptOrDecrypt(
	string text,
	int key
)
```

**VB**<br />
``` VB
Public Shared Function XorEncryptOrDecrypt ( 
	text As String,
	key As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim key As Integer
Dim returnValue As String

returnValue = CryptoUtil.XorEncryptOrDecrypt(text, 
	key)
```

**C++**<br />
``` C++
public:
static String^ XorEncryptOrDecrypt(
	String^ text, 
	int key
)
```

**F#**<br />
``` F#
static member XorEncryptOrDecrypt : 
        text : string * 
        key : int -> string 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to encrypt or decrypt.</dd><dt>key</dt><dd>Type: System.Int32<br />The key to use for encryption or decryption.</dd></dl>

#### Return Value
Type: String<br />The resulting encrypted or decrypted string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World"
Dim encrypted As String = XorText(str, 1)       ' Result: "Idmmn!Vnsme"
Dim decrypted As String = XorText(encrypted, 1) ' Result: "Hello World"
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />