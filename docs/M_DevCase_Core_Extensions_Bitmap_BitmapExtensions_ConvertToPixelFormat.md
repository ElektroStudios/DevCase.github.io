# BitmapExtensions.ConvertToPixelFormat Method 
 

Converts the piel format of the source Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap ConvertToPixelFormat(
	this Bitmap sender,
	PixelFormat format,
	bool disposeSourceImage = false
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ConvertToPixelFormat ( 
	sender As Bitmap,
	format As PixelFormat,
	Optional disposeSourceImage As Boolean = false
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
Dim format As PixelFormat
Dim disposeSourceImage As Boolean
Dim returnValue As Bitmap

returnValue = sender.ConvertToPixelFormat(format, 
	disposeSourceImage)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ ConvertToPixelFormat(
	Bitmap^ sender, 
	PixelFormat format, 
	bool disposeSourceImage = false
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ConvertToPixelFormat : 
        sender : Bitmap * 
        format : PixelFormat * 
        ?disposeSourceImage : bool 
(* Defaults:
        let _disposeSourceImage = defaultArg disposeSourceImage false
*)
-> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>format</dt><dd>Type: System.Drawing.Imaging.PixelFormat<br />The new pixel format.</dd><dt>disposeSourceImage (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), disposes the source Bitmap object.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting Bitmap.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />