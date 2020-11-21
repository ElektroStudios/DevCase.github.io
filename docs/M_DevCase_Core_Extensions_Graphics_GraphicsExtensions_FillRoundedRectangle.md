# GraphicsExtensions.FillRoundedRectangle Method 
 

Fills the interior of a rounded rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Graphics">DevCase.Core.Extensions.Graphics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void FillRoundedRectangle(
	this Graphics g,
	Brush brush,
	RectangleF rect,
	float cornerRadius
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub FillRoundedRectangle ( 
	g As Graphics,
	brush As Brush,
	rect As RectangleF,
	cornerRadius As Single
)
```

**VB Usage**<br />
``` VB Usage
Dim g As Graphics
Dim brush As Brush
Dim rect As RectangleF
Dim cornerRadius As Single

g.FillRoundedRectangle(brush, rect, 
	cornerRadius)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void FillRoundedRectangle(
	Graphics^ g, 
	Brush^ brush, 
	RectangleF rect, 
	float cornerRadius
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FillRoundedRectangle : 
        g : Graphics * 
        brush : Brush * 
        rect : RectangleF * 
        cornerRadius : float32 -> unit 

```


#### Parameters
&nbsp;<dl><dt>g</dt><dd>Type: System.Drawing.Graphics<br />The source Graphics.</dd><dt>brush</dt><dd>Type: System.Drawing.Brush<br />Brush that determines the characteristics of the fill.</dd><dt>rect</dt><dd>Type: System.Drawing.RectangleF<br />RectangleF structure that represents the rectangle to fill.</dd><dt>cornerRadius</dt><dd>Type: System.Single<br />Value that determine the corner radius of the rectangle specified in *rect* parameter.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Graphics. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rect As New Rectangle(New Point(0, 0), New Size(256, 256))
Dim radius As Integer = 10

Using g As Graphics = Me.CreateGraphics(), 
      pen As New Pen(Color.Red)

    g.FillRoundedRectangle(pen, rect, radius)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Graphics_GraphicsExtensions">GraphicsExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Graphics">DevCase.Core.Extensions.Graphics Namespace</a><br />