# BitmapExtensions.GetRegion Method 
 

Gets a region from the specified Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Region GetRegion(
	this Bitmap bitmap,
	Color transparencyKey,
	byte tolerance
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetRegion ( 
	bitmap As Bitmap,
	transparencyKey As Color,
	tolerance As Byte
) As Region
```

**VB Usage**<br />
``` VB Usage
Dim bitmap As Bitmap
Dim transparencyKey As Color
Dim tolerance As Byte
Dim returnValue As Region

returnValue = bitmap.GetRegion(transparencyKey, 
	tolerance)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Region^ GetRegion(
	Bitmap^ bitmap, 
	Color transparencyKey, 
	unsigned char tolerance
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetRegion : 
        bitmap : Bitmap * 
        transparencyKey : Color * 
        tolerance : byte -> Region 

```


#### Parameters
&nbsp;<dl><dt>bitmap</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>transparencyKey</dt><dd>Type: System.Drawing.Color<br />The transparency key.</dd><dt>tolerance</dt><dd>Type: System.Byte<br />The tolerance value. From 0 to 255.</dd></dl>

#### Return Value
Type: Region<br />The resulting Region.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example that demonstrates how to make a shape transparent Form. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Public Sub New()

        ' This call is required by the designer.
        InitializeComponent()

        ' Needed to make a custom shaped Form.
        Me.FormBorderStyle = FormBorderStyle.None
        Me.Width = Me.BackgroundImage.Width
        Me.Height = Me.BackgroundImage.Height

        ' Shape the Form
        Me.Region = Me.BackgroundImage.GetRegion(Color.FromArgb(0, 255, 0), 100)

    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />