# PointExtensions.Flip Method 
 

Flips the X,Y coordinates of the specified Point.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Point">DevCase.Core.Extensions.Point</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Point Flip(
	this Point sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Flip ( 
	sender As Point
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim sender As Point
Dim returnValue As Point

returnValue = sender.Flip()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Point Flip(
	Point sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Flip : 
        sender : Point -> Point 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Point<br />The source Point to flip.</dd></dl>

#### Return Value
Type: Point<br />The resulting Point.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Point. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Point_PointExtensions">PointExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Point">DevCase.Core.Extensions.Point Namespace</a><br />