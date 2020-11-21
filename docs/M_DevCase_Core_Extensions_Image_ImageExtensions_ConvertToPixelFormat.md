# ImageExtensions.ConvertToPixelFormat Method 
 

Converts the piel format of the source Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image ConvertToPixelFormat(
	this Image sender,
	PixelFormat format,
	bool disposeSourceImage = false
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ConvertToPixelFormat ( 
	sender As Image,
	format As PixelFormat,
	Optional disposeSourceImage As Boolean = false
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim format As PixelFormat
Dim disposeSourceImage As Boolean
Dim returnValue As Image

returnValue = sender.ConvertToPixelFormat(format, 
	disposeSourceImage)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ ConvertToPixelFormat(
	Image^ sender, 
	PixelFormat format, 
	bool disposeSourceImage = false
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ConvertToPixelFormat : 
        sender : Image * 
        format : PixelFormat * 
        ?disposeSourceImage : bool 
(* Defaults:
        let _disposeSourceImage = defaultArg disposeSourceImage false
*)
-> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>format</dt><dd>Type: System.Drawing.Imaging.PixelFormat<br />The new pixel format.</dd><dt>disposeSourceImage (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), disposes the source Image object.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />