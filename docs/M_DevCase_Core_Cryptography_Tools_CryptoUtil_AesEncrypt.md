# CryptoUtil.AesEncrypt Method 
 

Encrypts a string using AES algorithm.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string AesEncrypt(
	string str,
	string key,
	int size,
	byte[] salt = null,
	CipherMode mode = CipherMode.ECB,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function AesEncrypt ( 
	str As String,
	key As String,
	size As Integer,
	Optional salt As Byte() = Nothing,
	Optional mode As CipherMode = CipherMode.ECB,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim key As String
Dim size As Integer
Dim salt As Byte()
Dim mode As CipherMode
Dim enc As Encoding
Dim returnValue As String

returnValue = CryptoUtil.AesEncrypt(str, 
	key, size, salt, mode, enc)
```

**C++**<br />
``` C++
public:
static String^ AesEncrypt(
	String^ str, 
	String^ key, 
	int size, 
	array<unsigned char>^ salt = nullptr, 
	CipherMode mode = CipherMode::ECB, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member AesEncrypt : 
        str : string * 
        key : string * 
        size : int * 
        ?salt : byte[] * 
        ?mode : CipherMode * 
        ?enc : Encoding 
(* Defaults:
        let _salt = defaultArg salt null
        let _mode = defaultArg mode CipherMode.ECB
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to encrypt.</dd><dt>key</dt><dd>Type: System.String<br />The encryption key.</dd><dt>size</dt><dd>Type: System.Int32<br />The key size. 

`128`, `192` or `256` bits.</dd><dt>salt (Optional)</dt><dd>Type: System.Byte[]<br />The key salt.</dd><dt>mode (Optional)</dt><dd>Type: System.Security.Cryptography.CipherMode<br />The AES encryption mode.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The text Encoding.</dd></dl>

#### Return Value
Type: String<br />The encrypted string.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>A value of 128, 192 or 256 is required for AES algorithm.;size or Salt should contain at least 8 bytes.;salt</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim encrypted As String = CryptoUtil.AesEncrypt("Hello World!", "my key", 256)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />