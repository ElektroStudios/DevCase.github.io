# BitmapExtensions.ToGrayscale Method (Bitmap, GrayscaleLevel, GraphicsQualityContainer)
 

Transforms a Bitmap to grayscale colors.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap ToGrayscale(
	this Bitmap sender,
	GrayscaleLevel grayScaleLevel,
	GraphicsQualityContainer quality
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToGrayscale ( 
	sender As Bitmap,
	grayScaleLevel As GrayscaleLevel,
	quality As GraphicsQualityContainer
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
Dim grayScaleLevel As GrayscaleLevel
Dim quality As GraphicsQualityContainer
Dim returnValue As Bitmap

returnValue = sender.ToGrayscale(grayScaleLevel, 
	quality)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ ToGrayscale(
	Bitmap^ sender, 
	GrayscaleLevel grayScaleLevel, 
	GraphicsQualityContainer^ quality
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToGrayscale : 
        sender : Bitmap * 
        grayScaleLevel : GrayscaleLevel * 
        quality : GraphicsQualityContainer -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>grayScaleLevel</dt><dd>Type: <a href="T_DevCase_Core_Imaging_GrayscaleLevel">DevCase.Core.Imaging.GrayscaleLevel</a><br />The grayscale level.</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">DevCase.Core.Imaging.GraphicsQualityContainer</a><br />A <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">GraphicsQualityContainer</a> object that specifies the resulting image quality.</dd></dl>

#### Return Value
Type: Bitmap<br />The grayscaled Bitmap.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = Bitmap.FromFile("C:\File.png").ToGrayscale(GrayScaleTone.Light)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToGrayscale">ToGrayscale Overload</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />