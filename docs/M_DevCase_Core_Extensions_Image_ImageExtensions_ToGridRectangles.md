# ImageExtensions.ToGridRectangles Method 
 

Creates a grid from an Image with the specified columns and rows amount, then returns a IEnumerable(T) that contains each Rectangle of the grid.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<Rectangle> ToGridRectangles(
	this Image sender,
	int columns,
	int rows
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToGridRectangles ( 
	sender As Image,
	columns As Integer,
	rows As Integer
) As IEnumerable(Of Rectangle)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim columns As Integer
Dim rows As Integer
Dim returnValue As IEnumerable(Of Rectangle)

returnValue = sender.ToGridRectangles(columns, 
	rows)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<Rectangle>^ ToGridRectangles(
	Image^ sender, 
	int columns, 
	int rows
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToGridRectangles : 
        sender : Image * 
        columns : int * 
        rows : int -> IEnumerable<Rectangle> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>columns</dt><dd>Type: System.Int32<br />The columns amount.</dd><dt>rows</dt><dd>Type: System.Int32<br />The rows amount.</dd></dl>

#### Return Value
Type: IEnumerable(Rectangle)<br />A IEnumerable(T) that contains each Rectangle of the grid.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>columns or rows or sender</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = Bitmap.FromFile("C:\File.png")
Dim imgGrid As IEnumerable(Of Rectangle) = img.ToGridRectangles(columns:=6, rows:=4)
Dim pcbs As New List(Of PictureBox)

For Each sector As Rectangle In imgGrid

    Dim pcb As New PictureBox
    With pcb
        .BackgroundImageLayout = ImageLayout.None
        .BorderStyle = BorderStyle.Fixed3D
        .Size = sector.Size
        .Location = sector.Location
        .BackColor = Color.Teal
    End With

    pcbs.Add(pcb)

Next sector

Me.Controls.AddRange(pcbs.ToArray())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />