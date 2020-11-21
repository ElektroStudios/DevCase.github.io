# BitmapExtensions.Crop Method (Bitmap, Int32, Int32, Int32, Int32)
 

Crops a Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap Crop(
	this Bitmap sender,
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
	sender As Bitmap,
	x As Integer,
	y As Integer,
	width As Integer,
	height As Integer
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
Dim x As Integer
Dim y As Integer
Dim width As Integer
Dim height As Integer
Dim returnValue As Bitmap

returnValue = sender.Crop(x, y, width, 
	height)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ Crop(
	Bitmap^ sender, 
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
        sender : Bitmap * 
        x : int * 
        y : int * 
        width : int * 
        height : int -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>x</dt><dd>Type: System.Int32<br />The x coordinate.</dd><dt>y</dt><dd>Type: System.Int32<br />The y coordinate.</dd><dt>width</dt><dd>Type: System.Int32<br />The width.</dd><dt>height</dt><dd>Type: System.Int32<br />The height.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Crop">Crop Overload</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />