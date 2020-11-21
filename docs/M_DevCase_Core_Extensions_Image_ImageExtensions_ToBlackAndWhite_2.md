# ImageExtensions.ToBlackAndWhite Method (Image, Single, GraphicsQualityContainer)
 

Transforms an Image to black and white colors.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image ToBlackAndWhite(
	this Image sender,
	float threshold,
	GraphicsQualityContainer quality
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToBlackAndWhite ( 
	sender As Image,
	threshold As Single,
	quality As GraphicsQualityContainer
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim threshold As Single
Dim quality As GraphicsQualityContainer
Dim returnValue As Image

returnValue = sender.ToBlackAndWhite(threshold, 
	quality)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ ToBlackAndWhite(
	Image^ sender, 
	float threshold, 
	GraphicsQualityContainer^ quality
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToBlackAndWhite : 
        sender : Image * 
        threshold : float32 * 
        quality : GraphicsQualityContainer -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>threshold</dt><dd>Type: System.Single<br />The threshold.</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">DevCase.Core.Imaging.GraphicsQualityContainer</a><br />A <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">GraphicsQualityContainer</a> object that specifies the resulting image quality.</dd></dl>

#### Return Value
Type: Image<br />The black and white Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim quality As New GraphicsQualityContainer
quality.SmoothingMode = SmoothingMode.HighQuality
quality.InterpolationMode = InterpolationMode.HighQualityBicubic
quality.PixelOffsetMode = PixelOffsetMode.HighQuality

Dim img As Image = Bitmap.FromFile("C:\File.png").ToBlackAndWhite(threshold:=0.5F, quality)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Image_ImageExtensions_ToBlackAndWhite">ToBlackAndWhite Overload</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />