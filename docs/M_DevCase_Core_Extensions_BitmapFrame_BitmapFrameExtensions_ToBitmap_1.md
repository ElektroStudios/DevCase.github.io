# BitmapFrameExtensions.ToBitmap Method (BitmapFrame, PixelFormat)
 

Converts the source BitmapFrame to a Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_BitmapFrame">DevCase.Core.Extensions.BitmapFrame</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap ToBitmap(
	this BitmapFrame sender,
	PixelFormat pixelFormat
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToBitmap ( 
	sender As BitmapFrame,
	pixelFormat As PixelFormat
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As BitmapFrame
Dim pixelFormat As PixelFormat
Dim returnValue As Bitmap

returnValue = sender.ToBitmap(pixelFormat)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ ToBitmap(
	BitmapFrame^ sender, 
	PixelFormat pixelFormat
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToBitmap : 
        sender : BitmapFrame * 
        pixelFormat : PixelFormat -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Media.Imaging.BitmapFrame<br />The source BitmapFrame.</dd><dt>pixelFormat</dt><dd>Type: System.Drawing.Imaging.PixelFormat<br />The pixel format for the resulting bitmap.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting Bitmap

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type BitmapFrame. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Remarks
Credits to author: https://stackoverflow.com/a/2897325/1248295

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_BitmapFrame_BitmapFrameExtensions">BitmapFrameExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_BitmapFrame_BitmapFrameExtensions_ToBitmap">ToBitmap Overload</a><br /><a href="N_DevCase_Core_Extensions_BitmapFrame">DevCase.Core.Extensions.BitmapFrame Namespace</a><br />