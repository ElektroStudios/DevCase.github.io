# FreeImageUtil.GetThumbnail Method (Bitmap, Int32, Boolean)
 

Generates a thumbnail from the specified image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap GetThumbnail(
	Bitmap bmp,
	int squareSize,
	bool convert
)
```

**VB**<br />
``` VB
Public Shared Function GetThumbnail ( 
	bmp As Bitmap,
	squareSize As Integer,
	convert As Boolean
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim bmp As Bitmap
Dim squareSize As Integer
Dim convert As Boolean
Dim returnValue As Bitmap

returnValue = FreeImageUtil.GetThumbnail(bmp, 
	squareSize, convert)
```

**C++**<br />
``` C++
public:
static Bitmap^ GetThumbnail(
	Bitmap^ bmp, 
	int squareSize, 
	bool convert
)
```

**F#**<br />
``` F#
static member GetThumbnail : 
        bmp : Bitmap * 
        squareSize : int * 
        convert : bool -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>squareSize</dt><dd>Type: System.Int32<br />The thumbnail square size, in pixels.</dd><dt>convert</dt><dd>Type: System.Boolean<br />\[Missing <param name="convert"/> documentation for "M:DevCase.ThirdParty.FreeImage.FreeImageUtil.GetThumbnail(System.Drawing.Bitmap,System.Int32,System.Boolean)"\]</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting thumbnail.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FreeImage_FreeImageUtil">FreeImageUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_FreeImage_FreeImageUtil_GetThumbnail">GetThumbnail Overload</a><br /><a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />