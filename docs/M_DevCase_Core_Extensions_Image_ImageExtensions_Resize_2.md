# ImageExtensions.Resize Method (Image, Size, Boolean)
 

Resizes an Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image Resize(
	this Image sender,
	Size size,
	bool keepAspectRatio
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Resize ( 
	sender As Image,
	size As Size,
	keepAspectRatio As Boolean
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim size As Size
Dim keepAspectRatio As Boolean
Dim returnValue As Image

returnValue = sender.Resize(size, 
	keepAspectRatio)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ Resize(
	Image^ sender, 
	Size size, 
	bool keepAspectRatio
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Resize : 
        sender : Image * 
        size : Size * 
        keepAspectRatio : bool -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />The new size.</dd><dt>keepAspectRatio</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to preserve original image's aspect ratio; `false` (`False` in Visual Basic) otherwise.</dd></dl>

#### Return Value
Type: Image<br />The resized Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Value greater than 0 is required.;width or Value greater than 0 is required.;height</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Image_ImageExtensions_Resize">Resize Overload</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />