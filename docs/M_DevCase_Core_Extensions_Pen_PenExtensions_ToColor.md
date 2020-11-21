# PenExtensions.ToColor Method 
 

Converts a Pen to a Color.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Pen">DevCase.Core.Extensions.Pen</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Color ToColor(
	this Pen sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToColor ( 
	sender As Pen
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim sender As Pen
Dim returnValue As Color

returnValue = sender.ToColor()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Color ToColor(
	Pen^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToColor : 
        sender : Pen -> Color 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Pen<br />The source Pen.</dd></dl>

#### Return Value
Type: Color<br />A Color.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Pen. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Pen_PenExtensions">PenExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Pen">DevCase.Core.Extensions.Pen Namespace</a><br />