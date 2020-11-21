# CryptoUtil.AtbashEncrypt Method 
 

Encrypts a string using Atbash substitution cipher.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string AtbashEncrypt(
	string text
)
```

**VB**<br />
``` VB
Public Shared Function AtbashEncrypt ( 
	text As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim returnValue As String

returnValue = CryptoUtil.AtbashEncrypt(text)
```

**C++**<br />
``` C++
public:
static String^ AtbashEncrypt(
	String^ text
)
```

**F#**<br />
``` F#
static member AtbashEncrypt : 
        text : string -> string 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to encrypt.</dd></dl>

#### Return Value
Type: String<br />The encrypted string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim encrypted As String = AtbashEncrypt("Hello World!")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />