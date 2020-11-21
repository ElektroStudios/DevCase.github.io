# ImageUtil.GetIconCountFromExecutableFile Method 
 

Gets the total amount of icons stored in the specified executable, dll or icon file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int GetIconCountFromExecutableFile(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetIconCountFromExecutableFile ( 
	filepath As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Integer

returnValue = ImageUtil.GetIconCountFromExecutableFile(filepath)
```

**C++**<br />
``` C++
public:
static int GetIconCountFromExecutableFile(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetIconCountFromExecutableFile : 
        filepath : string -> int 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file path.</dd></dl>

#### Return Value
Type: Int32<br />\[Missing <returns> documentation for "M:DevCase.Core.Imaging.Tools.ImageUtil.GetIconCountFromExecutableFile(System.String)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim iconCount As Integer = GetIconCountFromFile("C:\Windows\Explorer.exe")
Dim bmp As Bitmap = ico.ToBitmap()
PictureBox1.BackgroundImage = bmp
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />