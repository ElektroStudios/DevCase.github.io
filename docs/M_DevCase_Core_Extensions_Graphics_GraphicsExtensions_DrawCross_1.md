# GraphicsExtensions.DrawCross Method (Graphics, Pen, PointF, Int32)
 

Draws a cross specified by a Point structure, up to the bounds of the source Graphics.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Graphics">DevCase.Core.Extensions.Graphics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void DrawCross(
	this Graphics g,
	Pen pen,
	PointF location,
	int spacing
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub DrawCross ( 
	g As Graphics,
	pen As Pen,
	location As PointF,
	spacing As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim g As Graphics
Dim pen As Pen
Dim location As PointF
Dim spacing As Integer

g.DrawCross(pen, location, spacing)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void DrawCross(
	Graphics^ g, 
	Pen^ pen, 
	PointF location, 
	int spacing
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DrawCross : 
        g : Graphics * 
        pen : Pen * 
        location : PointF * 
        spacing : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>g</dt><dd>Type: System.Drawing.Graphics<br />The source Graphics.</dd><dt>pen</dt><dd>Type: System.Drawing.Pen<br />Pen that determines the color, width, and style of the cross.</dd><dt>location</dt><dd>Type: System.Drawing.PointF<br />PointF that determines the position of the cross.</dd><dt>spacing</dt><dd>Type: System.Int32<br />Value that determines the opening spacing of the lines that converge at the center of the cross. 

 A value of zero (0) produces the same cross figure as calling <a href="M_DevCase_Core_Extensions_Graphics_GraphicsExtensions_DrawCross">DrawCross(Graphics, Pen, PointF)</a> method.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Graphics. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Graphics_GraphicsExtensions">GraphicsExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Graphics_GraphicsExtensions_DrawCross">DrawCross Overload</a><br /><a href="N_DevCase_Core_Extensions_Graphics">DevCase.Core.Extensions.Graphics Namespace</a><br />