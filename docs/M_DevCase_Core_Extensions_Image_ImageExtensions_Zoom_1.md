# ImageExtensions.Zoom Method (Image, Size, GraphicsQualityContainer, Color)
 

Enlarges the source Image within the specified canvas size, preserving aspect ratio. 

 The resulting effect is equal than using Zoom for BackgroundImageLayout property.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image Zoom(
	this Image image,
	Size size,
	GraphicsQualityContainer quality,
	Color fillColor
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Zoom ( 
	image As Image,
	size As Size,
	quality As GraphicsQualityContainer,
	fillColor As Color
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim image As Image
Dim size As Size
Dim quality As GraphicsQualityContainer
Dim fillColor As Color
Dim returnValue As Image

returnValue = image.Zoom(size, quality, 
	fillColor)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ Zoom(
	Image^ image, 
	Size size, 
	GraphicsQualityContainer^ quality, 
	Color fillColor
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Zoom : 
        image : Image * 
        size : Size * 
        quality : GraphicsQualityContainer * 
        fillColor : Color -> Image 

```


#### Parameters
&nbsp;<dl><dt>image</dt><dd>Type: System.Drawing.Image<br />\[Missing <param name="image"/> documentation for "M:DevCase.Core.Extensions.Image.ImageExtensions.Zoom(System.Drawing.Image,System.Drawing.Size,DevCase.Core.Imaging.GraphicsQualityContainer,System.Drawing.Color)"\]</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />\[Missing <param name="size"/> documentation for "M:DevCase.Core.Extensions.Image.ImageExtensions.Zoom(System.Drawing.Image,System.Drawing.Size,DevCase.Core.Imaging.GraphicsQualityContainer,System.Drawing.Color)"\]</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">DevCase.Core.Imaging.GraphicsQualityContainer</a><br />A <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">GraphicsQualityContainer</a> object that specifies the resulting image quality.</dd><dt>fillColor</dt><dd>Type: System.Drawing.Color<br />The color that will be used to fill any empty canvas space.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim srcImage As Image = Image.FromFile("C:\Image.jpg")
Dim sz As Size = Me.PictureBox1.ClientSize
Dim quality As New GraphicsQualityContainer()
Dim fillColor As Color = Color.Black
Dim dstImage As Image  = Zoom(srcImage, sz, quality, fillColor)

Me.PictureBox1.BackgroundImageLayout = ImageLayout.None
Me.PictureBox1.BackgroundImage = dstImage
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Image_ImageExtensions_Zoom">Zoom Overload</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />