# BitmapExtensions.SetBrightness Method (Bitmap, Single, GraphicsQualityContainer)
 

Adjusts the brightness of an Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap SetBrightness(
	this Bitmap sender,
	float brightness,
	GraphicsQualityContainer quality
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SetBrightness ( 
	sender As Bitmap,
	brightness As Single,
	quality As GraphicsQualityContainer
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
Dim brightness As Single
Dim quality As GraphicsQualityContainer
Dim returnValue As Bitmap

returnValue = sender.SetBrightness(brightness, 
	quality)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ SetBrightness(
	Bitmap^ sender, 
	float brightness, 
	GraphicsQualityContainer^ quality
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetBrightness : 
        sender : Bitmap * 
        brightness : float32 * 
        quality : GraphicsQualityContainer -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>brightness</dt><dd>Type: System.Single<br />The brightness. 

 Value is from range `0.0F` to `2.0F`, where `1.0F` is the current brightness.</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">DevCase.Core.Imaging.GraphicsQualityContainer</a><br />A <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">GraphicsQualityContainer</a> object that specifies the resulting image quality.</dd></dl>

#### Return Value
Type: Bitmap<br />The adjusted image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>brightness;Value between range from 0.0 to 2.0 is required.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim srcImage As Image = Bitmap.FromFile("C:\File.png")
Dim modImage As Image = srcImage.SetBrightness(1.5F)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetBrightness">SetBrightness Overload</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />