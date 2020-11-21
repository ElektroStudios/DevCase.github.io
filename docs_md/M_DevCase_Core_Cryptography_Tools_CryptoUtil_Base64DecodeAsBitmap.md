# CryptoUtil.Base64DecodeAsBitmap Method 
 

Decodes a string encoded in Base64 to a Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap Base64DecodeAsBitmap(
	string str
)
```

**VB**<br />
``` VB
Public Shared Function Base64DecodeAsBitmap ( 
	str As String
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim returnValue As Bitmap

returnValue = CryptoUtil.Base64DecodeAsBitmap(str)
```

**C++**<br />
``` C++
public:
static Bitmap^ Base64DecodeAsBitmap(
	String^ str
)
```

**F#**<br />
``` F#
static member Base64DecodeAsBitmap : 
        str : string -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The source Base64 encoded string.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting Bitmap.

## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />