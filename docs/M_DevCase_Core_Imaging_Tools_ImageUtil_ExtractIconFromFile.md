# ImageUtil.ExtractIconFromFile Method 
 

Extracts the icon associated for the specified file. 

 Note: the maximum size of the returned icon only can be 32x32.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Icon ExtractIconFromFile(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function ExtractIconFromFile ( 
	filepath As String
) As Icon
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Icon

returnValue = ImageUtil.ExtractIconFromFile(filepath)
```

**C++**<br />
``` C++
public:
static Icon^ ExtractIconFromFile(
	String^ filepath
)
```

**F#**<br />
``` F#
static member ExtractIconFromFile : 
        filepath : string -> Icon 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The full path to a file.</dd></dl>

#### Return Value
Type: Icon<br />The resulting icon.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim path As String = "C:\File.ext"
Dim ico As Icon = ExtractIconFromFile(path)
Dim bmp As Bitmap = ico.ToBitmap()
PictureBox1.BackgroundImage = bmp
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />