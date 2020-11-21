# ImageUtil.ExtractIconFromFileExtension Method 
 

Extracts the icon associated for the specified file extension. 

 Note: the maximum size of the returned icon only can be 32x32.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Icon ExtractIconFromFileExtension(
	string ext
)
```

**VB**<br />
``` VB
Public Shared Function ExtractIconFromFileExtension ( 
	ext As String
) As Icon
```

**VB Usage**<br />
``` VB Usage
Dim ext As String
Dim returnValue As Icon

returnValue = ImageUtil.ExtractIconFromFileExtension(ext)
```

**C++**<br />
``` C++
public:
static Icon^ ExtractIconFromFileExtension(
	String^ ext
)
```

**F#**<br />
``` F#
static member ExtractIconFromFileExtension : 
        ext : string -> Icon 

```


#### Parameters
&nbsp;<dl><dt>ext</dt><dd>Type: System.String<br />The file extension.</dd></dl>

#### Return Value
Type: Icon<br />The resulting icon.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ext As String = ".txt"
Dim ico As Icon = ExtractIconFromFileExtension(ext)
Dim bmp As Bitmap = ico.ToBitmap()
PictureBox1.BackgroundImage = bmp
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />