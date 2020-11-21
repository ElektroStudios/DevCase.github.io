# BitmapImageExtensions.ToBitmap Method (BitmapImage)
 

Converts the source BitmapImage to a Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_BitmapImage">DevCase.Core.Extensions.BitmapImage</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap ToBitmap(
	this BitmapImage sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToBitmap ( 
	sender As BitmapImage
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As BitmapImage
Dim returnValue As Bitmap

returnValue = sender.ToBitmap()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ ToBitmap(
	BitmapImage^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToBitmap : 
        sender : BitmapImage -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Media.Imaging.BitmapImage<br />The source BitmapImage.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting Bitmap

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type BitmapImage. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Remarks
Credits to author: https://stackoverflow.com/a/21931808/1248295

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_BitmapImage_BitmapImageExtensions">BitmapImageExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_BitmapImage_BitmapImageExtensions_ToBitmap">ToBitmap Overload</a><br /><a href="N_DevCase_Core_Extensions_BitmapImage">DevCase.Core.Extensions.BitmapImage Namespace</a><br />