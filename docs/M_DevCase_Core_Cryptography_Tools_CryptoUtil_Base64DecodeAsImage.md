# CryptoUtil.Base64DecodeAsImage Method 
 

Decodes a string encoded in Base64 to a Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image Base64DecodeAsImage(
	string str
)
```

**VB**<br />
``` VB
Public Shared Function Base64DecodeAsImage ( 
	str As String
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim returnValue As Image

returnValue = CryptoUtil.Base64DecodeAsImage(str)
```

**C++**<br />
``` C++
public:
static Image^ Base64DecodeAsImage(
	String^ str
)
```

**F#**<br />
``` F#
static member Base64DecodeAsImage : 
        str : string -> Image 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The source Base64 encoded string.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />