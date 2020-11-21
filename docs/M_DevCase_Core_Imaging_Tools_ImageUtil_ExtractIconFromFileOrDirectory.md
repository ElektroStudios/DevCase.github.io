# ImageUtil.ExtractIconFromFileOrDirectory Method 
 

Extracts the icon associated for the specified file or directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap ExtractIconFromFileOrDirectory(
	string itemPath,
	IconSizes iconSize
)
```

**VB**<br />
``` VB
Public Shared Function ExtractIconFromFileOrDirectory ( 
	itemPath As String,
	iconSize As IconSizes
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim itemPath As String
Dim iconSize As IconSizes
Dim returnValue As Bitmap

returnValue = ImageUtil.ExtractIconFromFileOrDirectory(itemPath, 
	iconSize)
```

**C++**<br />
``` C++
public:
static Bitmap^ ExtractIconFromFileOrDirectory(
	String^ itemPath, 
	IconSizes iconSize
)
```

**F#**<br />
``` F#
static member ExtractIconFromFileOrDirectory : 
        itemPath : string * 
        iconSize : IconSizes -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>itemPath</dt><dd>Type: System.String<br />The full path to a file or directory.</dd><dt>iconSize</dt><dd>Type: <a href="T_DevCase_Core_Imaging_IconSizes">DevCase.Core.Imaging.IconSizes</a><br />\[Missing <param name="iconSize"/> documentation for "M:DevCase.Core.Imaging.Tools.ImageUtil.ExtractIconFromFileOrDirectory(System.String,DevCase.Core.Imaging.IconSizes)"\]</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting icon.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim path As String = "C:\Windows"
Dim bmp As Bitmap = ExtractIconFromFileOrDirectory(path)
PictureBox1.BackgroundImage = bmp
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />