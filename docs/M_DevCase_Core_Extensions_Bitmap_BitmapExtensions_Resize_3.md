# BitmapExtensions.Resize Method (Bitmap, Size, Boolean, GraphicsQualityContainer)
 

Resizes an Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap Resize(
	this Bitmap sender,
	Size size,
	bool keepAspectRatio,
	GraphicsQualityContainer quality
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Resize ( 
	sender As Bitmap,
	size As Size,
	keepAspectRatio As Boolean,
	quality As GraphicsQualityContainer
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
Dim size As Size
Dim keepAspectRatio As Boolean
Dim quality As GraphicsQualityContainer
Dim returnValue As Bitmap

returnValue = sender.Resize(size, 
	keepAspectRatio, quality)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ Resize(
	Bitmap^ sender, 
	Size size, 
	bool keepAspectRatio, 
	GraphicsQualityContainer^ quality
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Resize : 
        sender : Bitmap * 
        size : Size * 
        keepAspectRatio : bool * 
        quality : GraphicsQualityContainer -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />The new size.</dd><dt>keepAspectRatio</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to preserve original image's aspect ratio; `false` (`False` in Visual Basic) otherwise.</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">DevCase.Core.Imaging.GraphicsQualityContainer</a><br />A <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">GraphicsQualityContainer</a> object that specifies the resulting image quality.</dd></dl>

#### Return Value
Type: Bitmap<br />The resized Bitmap.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Value greater than 0 is required.;width or Value greater than 0 is required.;height</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Resize">Resize Overload</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />