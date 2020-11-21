# ImageExtensions.SetOpacity Method (Image, Single)
 

Sets the opacity of an Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image SetOpacity(
	this Image sender,
	float opacity
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SetOpacity ( 
	sender As Image,
	opacity As Single
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim opacity As Single
Dim returnValue As Image

returnValue = sender.SetOpacity(opacity)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ SetOpacity(
	Image^ sender, 
	float opacity
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetOpacity : 
        sender : Image * 
        opacity : float32 -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>opacity</dt><dd>Type: System.Single<br />T The target opacity level, from `0.0` to `1.0`.</dd></dl>

#### Return Value
Type: Image<br />The Image with the opacity applied.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>opacity</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = Bitmap.FromFile("C:\File.png").SetOpacity(opacity:=0.5F)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Image_ImageExtensions_SetOpacity">SetOpacity Overload</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />