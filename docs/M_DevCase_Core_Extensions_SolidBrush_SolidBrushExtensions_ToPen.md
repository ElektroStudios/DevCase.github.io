# SolidBrushExtensions.ToPen Method 
 

Converts a SolidBrush to a Pen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_SolidBrush">DevCase.Core.Extensions.SolidBrush</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Pen ToPen(
	this SolidBrush sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToPen ( 
	sender As SolidBrush
) As Pen
```

**VB Usage**<br />
``` VB Usage
Dim sender As SolidBrush
Dim returnValue As Pen

returnValue = sender.ToPen()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Pen^ ToPen(
	SolidBrush^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToPen : 
        sender : SolidBrush -> Pen 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.SolidBrush<br />The source SolidBrush.</dd></dl>

#### Return Value
Type: Pen<br />A Pen.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SolidBrush. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_SolidBrush_SolidBrushExtensions">SolidBrushExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_SolidBrush">DevCase.Core.Extensions.SolidBrush Namespace</a><br />