# ImageExtensions.GetRegionReverse Method 
 

Gets a reversed region from the specified Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Region GetRegionReverse(
	this Image sender,
	Color transparencyKey,
	byte tolerance
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetRegionReverse ( 
	sender As Image,
	transparencyKey As Color,
	tolerance As Byte
) As Region
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim transparencyKey As Color
Dim tolerance As Byte
Dim returnValue As Region

returnValue = sender.GetRegionReverse(transparencyKey, 
	tolerance)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Region^ GetRegionReverse(
	Image^ sender, 
	Color transparencyKey, 
	unsigned char tolerance
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetRegionReverse : 
        sender : Image * 
        transparencyKey : Color * 
        tolerance : byte -> Region 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>transparencyKey</dt><dd>Type: System.Drawing.Color<br />The transparency key.</dd><dt>tolerance</dt><dd>Type: System.Byte<br />The tolerance value. From 0 to 255.</dd></dl>

#### Return Value
Type: Region<br />The resulting Region.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

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
        Me.Region = Me.BackgroundImage.GetRegionReverse(Color.FromArgb(0, 255, 0), 100)

    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />