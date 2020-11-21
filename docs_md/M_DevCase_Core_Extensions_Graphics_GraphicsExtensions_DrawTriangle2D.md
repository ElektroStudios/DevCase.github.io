# GraphicsExtensions.DrawTriangle2D Method (Graphics, Pen, Vector2, Vector2, Vector2)
 

Draws a two-dimensional triangle.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Graphics">DevCase.Core.Extensions.Graphics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void DrawTriangle2D(
	this Graphics g,
	Pen pen,
	Vector2 vector1,
	Vector2 vector2,
	Vector2 vector3
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub DrawTriangle2D ( 
	g As Graphics,
	pen As Pen,
	vector1 As Vector2,
	vector2 As Vector2,
	vector3 As Vector2
)
```

**VB Usage**<br />
``` VB Usage
Dim g As Graphics
Dim pen As Pen
Dim vector1 As Vector2
Dim vector2 As Vector2
Dim vector3 As Vector2

g.DrawTriangle2D(pen, vector1, vector2, 
	vector3)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void DrawTriangle2D(
	Graphics^ g, 
	Pen^ pen, 
	Vector2 vector1, 
	Vector2 vector2, 
	Vector2 vector3
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DrawTriangle2D : 
        g : Graphics * 
        pen : Pen * 
        vector1 : Vector2 * 
        vector2 : Vector2 * 
        vector3 : Vector2 -> unit 

```


#### Parameters
&nbsp;<dl><dt>g</dt><dd>Type: System.Drawing.Graphics<br />The source Graphics.</dd><dt>pen</dt><dd>Type: System.Drawing.Pen<br />Pen that determines the color, width, and style of the triangle.</dd><dt>vector1</dt><dd>Type: System.Numerics.Vector2<br />The first vector.</dd><dt>vector2</dt><dd>Type: System.Numerics.Vector2<br />The second vector.</dd><dt>vector3</dt><dd>Type: System.Numerics.Vector2<br />The third vector.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Graphics. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim v1 As New Vector2(50, 100)
Dim v2 As New Vector2(100, 50)
Dim v3 As New Vector2(150, 100)

Using g As Graphics = Me.CreateGraphics(), 
      pen As New Pen(Color.Red)

    g.DrawTriangle2D(v1, v2, v3)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Graphics_GraphicsExtensions">GraphicsExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Graphics_GraphicsExtensions_DrawTriangle2D">DrawTriangle2D Overload</a><br /><a href="N_DevCase_Core_Extensions_Graphics">DevCase.Core.Extensions.Graphics Namespace</a><br />