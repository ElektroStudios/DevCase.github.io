# ImageExtensions.Crop Method (Image, Int32, Int32, Int32, Int32)
 

Crops an Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image Crop(
	this Image sender,
	int x,
	int y,
	int width,
	int height
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Crop ( 
	sender As Image,
	x As Integer,
	y As Integer,
	width As Integer,
	height As Integer
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim x As Integer
Dim y As Integer
Dim width As Integer
Dim height As Integer
Dim returnValue As Image

returnValue = sender.Crop(x, y, width, 
	height)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ Crop(
	Image^ sender, 
	int x, 
	int y, 
	int width, 
	int height
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Crop : 
        sender : Image * 
        x : int * 
        y : int * 
        width : int * 
        height : int -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>x</dt><dd>Type: System.Int32<br />The x coordinate.</dd><dt>y</dt><dd>Type: System.Int32<br />The y coordinate.</dd><dt>width</dt><dd>Type: System.Int32<br />The width.</dd><dt>height</dt><dd>Type: System.Int32<br />The height.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Image_ImageExtensions_Crop">Crop Overload</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />