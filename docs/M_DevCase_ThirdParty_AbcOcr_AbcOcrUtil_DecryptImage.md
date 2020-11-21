# AbcOcrUtil.DecryptImage Method (Bitmap, String)
 

Decrypts a image into text.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_AbcOcr">DevCase.ThirdParty.AbcOcr</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DecryptImage(
	Bitmap image,
	string language = "eng"
)
```

**VB**<br />
``` VB
Public Shared Function DecryptImage ( 
	image As Bitmap,
	Optional language As String = "eng"
) As String
```

**VB Usage**<br />
``` VB Usage
Dim image As Bitmap
Dim language As String
Dim returnValue As String

returnValue = AbcOcrUtil.DecryptImage(image, 
	language)
```

**C++**<br />
``` C++
public:
static String^ DecryptImage(
	Bitmap^ image, 
	String^ language = L"eng"
)
```

**F#**<br />
``` F#
static member DecryptImage : 
        image : Bitmap * 
        ?language : string 
(* Defaults:
        let _language = defaultArg language "eng"
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>image</dt><dd>Type: System.Drawing.Bitmap<br />The captcha image to decrypt.</dd><dt>language (Optional)</dt><dd>Type: System.String<br />\[Missing <param name="language"/> documentation for "M:DevCase.ThirdParty.AbcOcr.AbcOcrUtil.DecryptImage(System.Drawing.Bitmap,System.String)"\]</dd></dl>

#### Return Value
Type: String<br />The resulting text.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As String = DecryptImage(New Bitmap("C:\Captcha.png"), "eng")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_AbcOcr_AbcOcrUtil">AbcOcrUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_AbcOcr_AbcOcrUtil_DecryptImage">DecryptImage Overload</a><br /><a href="N_DevCase_ThirdParty_AbcOcr">DevCase.ThirdParty.AbcOcr Namespace</a><br />