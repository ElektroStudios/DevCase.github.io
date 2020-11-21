# ImageExtensions.Flip Method 
 

Flips an Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image Flip(
	this Image sender,
	FlipType fliptype
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Flip ( 
	sender As Image,
	fliptype As FlipType
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim fliptype As FlipType
Dim returnValue As Image

returnValue = sender.Flip(fliptype)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ Flip(
	Image^ sender, 
	FlipType fliptype
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Flip : 
        sender : Image * 
        fliptype : FlipType -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>fliptype</dt><dd>Type: <a href="T_DevCase_Core_Imaging_FlipType">DevCase.Core.Imaging.FlipType</a><br />The flip type operation to perform.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />