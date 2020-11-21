# Vector2Extensions.ToPoint Method 
 

Converts a Vector2 to a Point.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Vector2">DevCase.Core.Extensions.Vector2</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Point ToPoint(
	this Vector2 vector
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToPoint ( 
	vector As Vector2
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim vector As Vector2
Dim returnValue As Point

returnValue = vector.ToPoint()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Point ToPoint(
	Vector2 vector
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToPoint : 
        vector : Vector2 -> Point 

```


#### Parameters
&nbsp;<dl><dt>vector</dt><dd>Type: System.Numerics.Vector2<br />The source Vector2.</dd></dl>

#### Return Value
Type: Point<br />The resulting Point.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Vector2. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Vector2_Vector2Extensions">Vector2Extensions Class</a><br /><a href="N_DevCase_Core_Extensions_Vector2">DevCase.Core.Extensions.Vector2 Namespace</a><br />