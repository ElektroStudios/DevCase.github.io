# ImageUtil.ExtractIconFromExecutableFile Method (String, Int32, Int32)
 

Extracts a icon stored in the specified executable, dll or icon file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Icon ExtractIconFromExecutableFile(
	string filepath,
	int iconIndex,
	int iconSize
)
```

**VB**<br />
``` VB
Public Shared Function ExtractIconFromExecutableFile ( 
	filepath As String,
	iconIndex As Integer,
	iconSize As Integer
) As Icon
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim iconIndex As Integer
Dim iconSize As Integer
Dim returnValue As Icon

returnValue = ImageUtil.ExtractIconFromExecutableFile(filepath, 
	iconIndex, iconSize)
```

**C++**<br />
``` C++
public:
static Icon^ ExtractIconFromExecutableFile(
	String^ filepath, 
	int iconIndex, 
	int iconSize
)
```

**F#**<br />
``` F#
static member ExtractIconFromExecutableFile : 
        filepath : string * 
        iconIndex : int * 
        iconSize : int -> Icon 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source filepath.</dd><dt>iconIndex</dt><dd>Type: System.Int32<br />The index of the icon to be extracted.</dd><dt>iconSize</dt><dd>Type: System.Int32<br />The icon size, in pixels.</dd></dl>

#### Return Value
Type: Icon<br />\[Missing <returns> documentation for "M:DevCase.Core.Imaging.Tools.ImageUtil.ExtractIconFromExecutableFile(System.String,System.Int32,System.Int32)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ico As Icon = ExtractIconFromExecutableFile("C:\Windows\Explorer.exe", 0, 256)
Dim bmp As Bitmap = ico.ToBitmap()
PictureBox1.BackgroundImage = bmp
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_ExtractIconFromExecutableFile">ExtractIconFromExecutableFile Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />