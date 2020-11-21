# FreeImageUtil.Convert Method (Bitmap, String, FREE_IMAGE_FORMAT, FREE_IMAGE_SAVE_FLAGS)
 

Converts the format of the specified image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Convert(
	Bitmap bmp,
	string output,
	FREE_IMAGE_FORMAT newFormat,
	FREE_IMAGE_SAVE_FLAGS saveFlags = FREE_IMAGE_SAVE_FLAGS.DEFAULT
)
```

**VB**<br />
``` VB
Public Shared Sub Convert ( 
	bmp As Bitmap,
	output As String,
	newFormat As FREE_IMAGE_FORMAT,
	Optional saveFlags As FREE_IMAGE_SAVE_FLAGS = FREE_IMAGE_SAVE_FLAGS.DEFAULT
)
```

**VB Usage**<br />
``` VB Usage
Dim bmp As Bitmap
Dim output As String
Dim newFormat As FREE_IMAGE_FORMAT
Dim saveFlags As FREE_IMAGE_SAVE_FLAGSFreeImageUtil.Convert(bmp, output, newFormat, 
	saveFlags)
```

**C++**<br />
``` C++
public:
static void Convert(
	Bitmap^ bmp, 
	String^ output, 
	FREE_IMAGE_FORMAT newFormat, 
	FREE_IMAGE_SAVE_FLAGS saveFlags = FREE_IMAGE_SAVE_FLAGS::DEFAULT
)
```

**F#**<br />
``` F#
static member Convert : 
        bmp : Bitmap * 
        output : string * 
        newFormat : FREE_IMAGE_FORMAT * 
        ?saveFlags : FREE_IMAGE_SAVE_FLAGS 
(* Defaults:
        let _saveFlags = defaultArg saveFlags FREE_IMAGE_SAVE_FLAGS.DEFAULT
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>output</dt><dd>Type: System.String<br />The output filepath.</dd><dt>newFormat</dt><dd>Type: FREE_IMAGE_FORMAT<br />The new image format.</dd><dt>saveFlags (Optional)</dt><dd>Type: FREE_IMAGE_SAVE_FLAGS<br />Additional flags.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FreeImage_FreeImageUtil">FreeImageUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_FreeImage_FreeImageUtil_Convert">Convert Overload</a><br /><a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />