# ImageExtensions.ToGrayscale Method (Image, GrayscaleLevel)
 

Transforms an Image to grayscale colors.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image ToGrayscale(
	this Image sender,
	GrayscaleLevel grayScaleLevel
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToGrayscale ( 
	sender As Image,
	grayScaleLevel As GrayscaleLevel
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim grayScaleLevel As GrayscaleLevel
Dim returnValue As Image

returnValue = sender.ToGrayscale(grayScaleLevel)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ ToGrayscale(
	Image^ sender, 
	GrayscaleLevel grayScaleLevel
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToGrayscale : 
        sender : Image * 
        grayScaleLevel : GrayscaleLevel -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>grayScaleLevel</dt><dd>Type: <a href="T_DevCase_Core_Imaging_GrayscaleLevel">DevCase.Core.Imaging.GrayscaleLevel</a><br />The grayscale level.</dd></dl>

#### Return Value
Type: Image<br />The grayscaled Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = Bitmap.FromFile("C:\File.png").ToGrayscale(GrayScaleTone.Light)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Image_ImageExtensions_ToGrayscale">ToGrayscale Overload</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />