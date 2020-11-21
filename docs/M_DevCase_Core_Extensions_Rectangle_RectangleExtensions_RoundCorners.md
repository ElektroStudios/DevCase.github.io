# RectangleExtensions.RoundCorners Method 
 

Returns a GraphicsPath that represents the source Rectangle with its top-left, top-right, bottom-left and bottom-right corners rounded by the specified radius value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Rectangle">DevCase.Core.Extensions.Rectangle</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static GraphicsPath RoundCorners(
	this Rectangle rect,
	int cornerRadius
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function RoundCorners ( 
	rect As Rectangle,
	cornerRadius As Integer
) As GraphicsPath
```

**VB Usage**<br />
``` VB Usage
Dim rect As Rectangle
Dim cornerRadius As Integer
Dim returnValue As GraphicsPath

returnValue = rect.RoundCorners(cornerRadius)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static GraphicsPath^ RoundCorners(
	Rectangle rect, 
	int cornerRadius
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RoundCorners : 
        rect : Rectangle * 
        cornerRadius : int -> GraphicsPath 

```


#### Parameters
&nbsp;<dl><dt>rect</dt><dd>Type: System.Drawing.Rectangle<br />The source Rectangle.</dd><dt>cornerRadius</dt><dd>Type: System.Int32<br />Value that determine the corner radius of the rectangle.</dd></dl>

#### Return Value
Type: GraphicsPath<br />\[Missing <returns> documentation for "M:DevCase.Core.Extensions.Rectangle.RectangleExtensions.RoundCorners(System.Drawing.Rectangle,System.Int32)"\]

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Rectangle. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rect As New Rectangle(New Point(0, 0), New Size(256, 256))
Dim radius As Integer = 10

Dim roundedRect As GraphicsPath = RoundCorners(rect, radius)

Using g As Graphics = Me.CreateGraphics(), 
      pen As New Pen(Color.Red)

    g.DrawPath(pen, roundedRect)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Rectangle_RectangleExtensions">RectangleExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Rectangle">DevCase.Core.Extensions.Rectangle Namespace</a><br />