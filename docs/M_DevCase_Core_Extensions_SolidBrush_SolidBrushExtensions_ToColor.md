# SolidBrushExtensions.ToColor Method 
 

Converts a SolidBrush to a Color.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_SolidBrush">DevCase.Core.Extensions.SolidBrush</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Color ToColor(
	this SolidBrush sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToColor ( 
	sender As SolidBrush
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim sender As SolidBrush
Dim returnValue As Color

returnValue = sender.ToColor()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Color ToColor(
	SolidBrush^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToColor : 
        sender : SolidBrush -> Color 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.SolidBrush<br />The source SolidBrush.</dd></dl>

#### Return Value
Type: Color<br />A Color.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SolidBrush. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_SolidBrush_SolidBrushExtensions">SolidBrushExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_SolidBrush">DevCase.Core.Extensions.SolidBrush Namespace</a><br />