# BitmapExtensions.ApplyColorMatrix Method (Bitmap, ColorMatrix)
 

Applies a custom color matrix to an Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap ApplyColorMatrix(
	this Bitmap sender,
	ColorMatrix colorMatrix
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ApplyColorMatrix ( 
	sender As Bitmap,
	colorMatrix As ColorMatrix
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
Dim colorMatrix As ColorMatrix
Dim returnValue As Bitmap

returnValue = sender.ApplyColorMatrix(colorMatrix)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ ApplyColorMatrix(
	Bitmap^ sender, 
	ColorMatrix^ colorMatrix
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ApplyColorMatrix : 
        sender : Bitmap * 
        colorMatrix : ColorMatrix -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>colorMatrix</dt><dd>Type: System.Drawing.Imaging.ColorMatrix<br />The color matrix to apply to the source image.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting Bitmap.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim grayscaleMatrix As New ColorMatrix({New Single() {0.3F, 0.3F, 0.3F, 0, 0},
                                        New Single() {0.59F, 0.59F, 0.59F, 0, 0},
                                        New Single() {0.11F, 0.11F, 0.11F, 0, 0},
                                        New Single() {0, 0, 0, 1, 0},
                                        New Single() {0, 0, 0, 0, 1}})

Dim bmp As Bitmap = Bitmap.FromFile("C:\File.png").ApplyColorMatrix(grayscaleMatrix)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ApplyColorMatrix">ApplyColorMatrix Overload</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />