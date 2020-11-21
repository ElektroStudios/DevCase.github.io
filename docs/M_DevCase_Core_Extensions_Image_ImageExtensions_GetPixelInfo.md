# ImageExtensions.GetPixelInfo Method 
 

For each pixel in the source image, gets the Color, pixel position, and coordinates location respectivelly to the image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<PixelInfo> GetPixelInfo(
	this Image sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetPixelInfo ( 
	sender As Image
) As IEnumerable(Of PixelInfo)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim returnValue As IEnumerable(Of PixelInfo)

returnValue = sender.GetPixelInfo()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<PixelInfo^>^ GetPixelInfo(
	Image^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetPixelInfo : 
        sender : Image -> IEnumerable<PixelInfo> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />\[Missing <param name="sender"/> documentation for "M:DevCase.Core.Extensions.Image.ImageExtensions.GetPixelInfo(System.Drawing.Image)"\]</dd></dl>

#### Return Value
Type: IEnumerable(<a href="T_DevCase_Core_Imaging_PixelInfo">PixelInfo</a>)<br />A IEnumerable(T) containing the Color, pixel position, and coordinates location respectivelly to the image, of each pixel in the image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim color As Color = color.FromArgb(117, 228, 26)
Dim bmp As Bitmap = CreateSolidcolorBitmap(New Size(2, 2), color, PixelFormat.Format32bppArgb)
Dim pxInfoCol As IEnumerable(Of PixelInfo) = bmp.GetPixelInfo()

For Each pxInfo As PixelInfo In pxInfoCol
    Console.WriteLine(String.Format("Position: {0}, Location: {1}, Color: {2}",
                                    pxInfo.Position, pxInfo.Location.ToString(), pxInfo.Color.ToString()))
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />