# RectangleExtensions.ToRectangleF Method 
 

Converts a Rectangle to a RectangleF.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Rectangle">DevCase.Core.Extensions.Rectangle</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static RectangleF ToRectangleF(
	this Rectangle sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToRectangleF ( 
	sender As Rectangle
) As RectangleF
```

**VB Usage**<br />
``` VB Usage
Dim sender As Rectangle
Dim returnValue As RectangleF

returnValue = sender.ToRectangleF()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static RectangleF ToRectangleF(
	Rectangle sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToRectangleF : 
        sender : Rectangle -> RectangleF 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Rectangle<br />The source Rectangle.</dd></dl>

#### Return Value
Type: RectangleF<br />The resulting RectangleF.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Rectangle. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Rectangle_RectangleExtensions">RectangleExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Rectangle">DevCase.Core.Extensions.Rectangle Namespace</a><br />