# BitmapExtensions.Zoom Method (Bitmap, Size, GraphicsQualityContainer, Color)
 

Enlarges the source Bitmap within the specified canvas size, preserving its aspect ratio. 

 The resulting effect is equal than using Zoom for BackgroundImageLayout property.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap Zoom(
	this Bitmap image,
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
	image As Bitmap,
	size As Size,
	quality As GraphicsQualityContainer,
	fillColor As Color
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim image As Bitmap
Dim size As Size
Dim quality As GraphicsQualityContainer
Dim fillColor As Color
Dim returnValue As Bitmap

returnValue = image.Zoom(size, quality, 
	fillColor)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ Zoom(
	Bitmap^ image, 
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
        image : Bitmap * 
        size : Size * 
        quality : GraphicsQualityContainer * 
        fillColor : Color -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>image</dt><dd>Type: System.Drawing.Bitmap<br />\[Missing <param name="image"/> documentation for "M:DevCase.Core.Extensions.Bitmap.BitmapExtensions.Zoom(System.Drawing.Bitmap,System.Drawing.Size,DevCase.Core.Imaging.GraphicsQualityContainer,System.Drawing.Color)"\]</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />\[Missing <param name="size"/> documentation for "M:DevCase.Core.Extensions.Bitmap.BitmapExtensions.Zoom(System.Drawing.Bitmap,System.Drawing.Size,DevCase.Core.Imaging.GraphicsQualityContainer,System.Drawing.Color)"\]</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">DevCase.Core.Imaging.GraphicsQualityContainer</a><br />A <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">GraphicsQualityContainer</a> object that specifies the resulting image quality.</dd><dt>fillColor</dt><dd>Type: System.Drawing.Color<br />The color that will be used to fill any empty canvas space.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting Bitmap.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim srcImage As Bitmap = Image.FromFile("C:\Image.jpg")
Dim sz As Size = Me.PictureBox1.ClientSize
Dim quality As New GraphicsQualityContainer()
Dim fillColor As Color = Color.Black
Dim dstImage As Bitmap  = Zoom(srcImage, sz, quality, fillColor)

Me.PictureBox1.BackgroundImageLayout = ImageLayout.None
Me.PictureBox1.BackgroundImage = dstImage
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Zoom">Zoom Overload</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />