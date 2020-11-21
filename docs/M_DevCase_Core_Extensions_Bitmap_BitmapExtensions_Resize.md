# BitmapExtensions.Resize Method (Bitmap, Double, Boolean)
 

Resizes an Bitmap by the given percentage.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap Resize(
	this Bitmap sender,
	double percent,
	bool keepAspectRatio
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Resize ( 
	sender As Bitmap,
	percent As Double,
	keepAspectRatio As Boolean
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
Dim percent As Double
Dim keepAspectRatio As Boolean
Dim returnValue As Bitmap

returnValue = sender.Resize(percent, 
	keepAspectRatio)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ Resize(
	Bitmap^ sender, 
	double percent, 
	bool keepAspectRatio
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Resize : 
        sender : Bitmap * 
        percent : float * 
        keepAspectRatio : bool -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>percent</dt><dd>Type: System.Double<br />The percentage.</dd><dt>keepAspectRatio</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to preserve original image's aspect ratio; `false` (`False` in Visual Basic) otherwise.</dd></dl>

#### Return Value
Type: Bitmap<br />The resized Bitmap.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Resize">Resize Overload</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />