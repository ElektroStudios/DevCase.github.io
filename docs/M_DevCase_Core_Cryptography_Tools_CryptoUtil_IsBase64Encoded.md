# CryptoUtil.IsBase64Encoded Method 
 

Determines whether the source string has been `Base64` encoded.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsBase64Encoded(
	string value
)
```

**VB**<br />
``` VB
Public Shared Function IsBase64Encoded ( 
	value As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim value As String
Dim returnValue As Boolean

returnValue = CryptoUtil.IsBase64Encoded(value)
```

**C++**<br />
``` C++
public:
static bool IsBase64Encoded(
	String^ value
)
```

**F#**<br />
``` F#
static member IsBase64Encoded : 
        value : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.String<br />The string to analyze.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the source string has been `Base64` encoded, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isEncoded As String = IsBase64Encoded("SGVsbG8gV29ybGQh")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />