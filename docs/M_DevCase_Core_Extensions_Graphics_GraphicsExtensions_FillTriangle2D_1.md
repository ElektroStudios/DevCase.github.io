# GraphicsExtensions.FillTriangle2D Method (Graphics, Brush, Vector3, Vector3, Vector3)
 

Fills the interior of a two-dimensional triangle.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Graphics">DevCase.Core.Extensions.Graphics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void FillTriangle2D(
	this Graphics g,
	Brush brush,
	Vector3 vector1,
	Vector3 vector2,
	Vector3 vector3
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub FillTriangle2D ( 
	g As Graphics,
	brush As Brush,
	vector1 As Vector3,
	vector2 As Vector3,
	vector3 As Vector3
)
```

**VB Usage**<br />
``` VB Usage
Dim g As Graphics
Dim brush As Brush
Dim vector1 As Vector3
Dim vector2 As Vector3
Dim vector3 As Vector3

g.FillTriangle2D(brush, vector1, vector2, 
	vector3)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void FillTriangle2D(
	Graphics^ g, 
	Brush^ brush, 
	Vector3 vector1, 
	Vector3 vector2, 
	Vector3 vector3
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FillTriangle2D : 
        g : Graphics * 
        brush : Brush * 
        vector1 : Vector3 * 
        vector2 : Vector3 * 
        vector3 : Vector3 -> unit 

```


#### Parameters
&nbsp;<dl><dt>g</dt><dd>Type: System.Drawing.Graphics<br />The source Graphics.</dd><dt>brush</dt><dd>Type: System.Drawing.Brush<br />Brush that determines the characteristics of the fill.</dd><dt>vector1</dt><dd>Type: System.Numerics.Vector3<br />The first vector.</dd><dt>vector2</dt><dd>Type: System.Numerics.Vector3<br />The second vector.</dd><dt>vector3</dt><dd>Type: System.Numerics.Vector3<br />The third vector.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Graphics. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim v1 As New Vector3(50, 100, 0)
Dim v2 As New Vector3(100, 50, 0)
Dim v3 As New Vector3(150, 100, 0)

Using g As Graphics = Me.CreateGraphics(), 
      pen As New Pen(Color.Red)

    g.FillTriangle2D(v1, v2, v3)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Graphics_GraphicsExtensions">GraphicsExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Graphics_GraphicsExtensions_FillTriangle2D">FillTriangle2D Overload</a><br /><a href="N_DevCase_Core_Extensions_Graphics">DevCase.Core.Extensions.Graphics Namespace</a><br />