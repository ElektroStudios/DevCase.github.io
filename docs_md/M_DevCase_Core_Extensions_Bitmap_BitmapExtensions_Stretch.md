# BitmapExtensions.Stretch Method 
 

Stretches the source Bitmap within the specified canvas size. 

 The resulting effect is equal than using Stretch for BackgroundImageLayout property.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap Stretch(
	this Bitmap image,
	Size size,
	GraphicsQualityContainer quality
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Stretch ( 
	image As Bitmap,
	size As Size,
	quality As GraphicsQualityContainer
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim image As Bitmap
Dim size As Size
Dim quality As GraphicsQualityContainer
Dim returnValue As Bitmap

returnValue = image.Stretch(size, 
	quality)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ Stretch(
	Bitmap^ image, 
	Size size, 
	GraphicsQualityContainer^ quality
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Stretch : 
        image : Bitmap * 
        size : Size * 
        quality : GraphicsQualityContainer -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>image</dt><dd>Type: System.Drawing.Bitmap<br />\[Missing <param name="image"/> documentation for "M:DevCase.Core.Extensions.Bitmap.BitmapExtensions.Stretch(System.Drawing.Bitmap,System.Drawing.Size,DevCase.Core.Imaging.GraphicsQualityContainer)"\]</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />\[Missing <param name="size"/> documentation for "M:DevCase.Core.Extensions.Bitmap.BitmapExtensions.Stretch(System.Drawing.Bitmap,System.Drawing.Size,DevCase.Core.Imaging.GraphicsQualityContainer)"\]</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">DevCase.Core.Imaging.GraphicsQualityContainer</a><br />A <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">GraphicsQualityContainer</a> object that specifies the resulting image quality.</dd></dl>

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
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />