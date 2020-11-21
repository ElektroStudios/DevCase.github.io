# ImageExtensions.GetPixelInfoAt Method 
 

Gets a <a href="T_DevCase_Core_Imaging_PixelInfo">PixelInfo</a> instance that contains the Color, pixel position, and coordinates location respectivelly to the image, of the pixel at the specified pixel position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static PixelInfo GetPixelInfoAt(
	this Image sender,
	int position
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetPixelInfoAt ( 
	sender As Image,
	position As Integer
) As PixelInfo
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim position As Integer
Dim returnValue As PixelInfo

returnValue = sender.GetPixelInfoAt(position)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static PixelInfo^ GetPixelInfoAt(
	Image^ sender, 
	int position
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetPixelInfoAt : 
        sender : Image * 
        position : int -> PixelInfo 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />\[Missing <param name="sender"/> documentation for "M:DevCase.Core.Extensions.Image.ImageExtensions.GetPixelInfoAt(System.Drawing.Image,System.Int32)"\]</dd><dt>position</dt><dd>Type: System.Int32<br />\[Missing <param name="position"/> documentation for "M:DevCase.Core.Extensions.Image.ImageExtensions.GetPixelInfoAt(System.Drawing.Image,System.Int32)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Imaging_PixelInfo">PixelInfo</a><br />A <a href="T_DevCase_Core_Imaging_PixelInfo">PixelInfo</a> instance that contains the Color, pixel position, and coordinates location respectivelly to the image, of the pixel at the specified pixel position.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>position</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim color As Color = color.FromArgb(117, 228, 26)
Dim bmp As Bitmap = CreateSolidcolorBitmap(New Size(1, 1), color, PixelFormat.Format32bppArgb)
Dim pxInfo AsPixelInfo = bmp.GetPixelInfoAt(1)

Console.WriteLine(String.Format("Position: {0}, Location: {1}, Color: {2}",
                                pxInfo.Position, pxInfo.Location.ToString(), pxInfo.Color.ToString()))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />