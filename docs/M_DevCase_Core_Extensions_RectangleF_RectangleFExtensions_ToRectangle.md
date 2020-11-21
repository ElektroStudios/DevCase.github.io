# RectangleFExtensions.ToRectangle Method 
 

Converts a RectangleF to a Rectangle, by rounding the RectangleF values to the nearest integer values.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Rectangle ToRectangle(
	this RectangleF sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToRectangle ( 
	sender As RectangleF
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim sender As RectangleF
Dim returnValue As Rectangle

returnValue = sender.ToRectangle()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Rectangle ToRectangle(
	RectangleF sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToRectangle : 
        sender : RectangleF -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.RectangleF<br />The source RectangleF.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RectangleF. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_RectangleF_RectangleFExtensions">RectangleFExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF Namespace</a><br />