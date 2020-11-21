# ImageExtensions.IndexOf Method (Image, Color, Int32)
 

Reports the zero-based pixel index of the first occurrence of the specified Color in this image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int IndexOf(
	this Image sender,
	Color color,
	int startIndex
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IndexOf ( 
	sender As Image,
	color As Color,
	startIndex As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim color As Color
Dim startIndex As Integer
Dim returnValue As Integer

returnValue = sender.IndexOf(color, 
	startIndex)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int IndexOf(
	Image^ sender, 
	Color color, 
	int startIndex
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IndexOf : 
        sender : Image * 
        color : Color * 
        startIndex : int -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>color</dt><dd>Type: System.Drawing.Color<br />The Color to find.</dd><dt>startIndex</dt><dd>Type: System.Int32<br />The search starting pixel position.</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index position of the Color found, otherwise, `-1`.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NotImplementedException</td><td>Only PixelFormats that has 3 or 4 bytes-per-pixel are supported.</td></tr><tr><td>ArgumentOutOfRangeException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim color As Color = Color.FromArgb(117, 228, 26)
Dim bmp As Bitmap = CreateSolidcolorBitmap(New Size(256, 256), color, PixelFormat.Format32bppArgb)
Dim indexOfColor As Integer = bmp.IndexOf(color, startIndex:=0)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Image_ImageExtensions_IndexOf">IndexOf Overload</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />