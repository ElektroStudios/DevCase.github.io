# CryptoUtil.AtbashDecrypt Method 
 

Decrypts a string using Atbash substitution cipher.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string AtbashDecrypt(
	string text
)
```

**VB**<br />
``` VB
Public Shared Function AtbashDecrypt ( 
	text As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim returnValue As String

returnValue = CryptoUtil.AtbashDecrypt(text)
```

**C++**<br />
``` C++
public:
static String^ AtbashDecrypt(
	String^ text
)
```

**F#**<br />
``` F#
static member AtbashDecrypt : 
        text : string -> string 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to decrypt.</dd></dl>

#### Return Value
Type: String<br />The decrypted string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim encrypted As String = AtbashDecrypt("Svool Dliow!")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />