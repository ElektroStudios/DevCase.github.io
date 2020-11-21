# RectangleFExtensions.RoundCorners Method 
 

Returns a GraphicsPath that represents the source RectangleF with its top-left, top-right, bottom-left and bottom-right corners rounded by the specified radius value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static GraphicsPath RoundCorners(
	this RectangleF rect,
	float cornerRadius
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function RoundCorners ( 
	rect As RectangleF,
	cornerRadius As Single
) As GraphicsPath
```

**VB Usage**<br />
``` VB Usage
Dim rect As RectangleF
Dim cornerRadius As Single
Dim returnValue As GraphicsPath

returnValue = rect.RoundCorners(cornerRadius)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static GraphicsPath^ RoundCorners(
	RectangleF rect, 
	float cornerRadius
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RoundCorners : 
        rect : RectangleF * 
        cornerRadius : float32 -> GraphicsPath 

```


#### Parameters
&nbsp;<dl><dt>rect</dt><dd>Type: System.Drawing.RectangleF<br />The source RectangleF.</dd><dt>cornerRadius</dt><dd>Type: System.Single<br />Value that determine the corner radius of the rectangle.</dd></dl>

#### Return Value
Type: GraphicsPath<br />\[Missing <returns> documentation for "M:DevCase.Core.Extensions.RectangleF.RectangleFExtensions.RoundCorners(System.Drawing.RectangleF,System.Single)"\]

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RectangleF. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Remarks
Original source-code: <a href="https://stackoverflow.com/a/33853557/1248295" target="_blank">https://stackoverflow.com/a/33853557/1248295</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rect As New RectangleF(New PointF(0, 0), New SizeF(256, 256))
Dim radius As Single = 10

Dim roundedRect As GraphicsPath = RoundCorners(rect, radius)

Using g As Graphics = Me.CreateGraphics(), 
      pen As New Pen(Color.Red)

    g.DrawPath(pen, roundedRect)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_RectangleF_RectangleFExtensions">RectangleFExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF Namespace</a><br />