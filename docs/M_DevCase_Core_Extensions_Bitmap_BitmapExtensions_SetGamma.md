# BitmapExtensions.SetGamma Method (Bitmap, Single)
 

Adjusts the gamma of an Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap SetGamma(
	this Bitmap sender,
	float gamma
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SetGamma ( 
	sender As Bitmap,
	gamma As Single
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
Dim gamma As Single
Dim returnValue As Bitmap

returnValue = sender.SetGamma(gamma)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ SetGamma(
	Bitmap^ sender, 
	float gamma
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetGamma : 
        sender : Bitmap * 
        gamma : float32 -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>gamma</dt><dd>Type: System.Single<br />The gamma. 

 Value is from range `0.0F` to `2.0F`, where `1.0F` is the current gamma.</dd></dl>

#### Return Value
Type: Bitmap<br />The adjusted image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>gamma;Value between range from 0.0 to 2.0 is required.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim srcImage As Image = Bitmap.FromFile("C:\File.png")
Dim modImage As Image = srcImage.SetGamma(1.5F)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetGamma">SetGamma Overload</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />