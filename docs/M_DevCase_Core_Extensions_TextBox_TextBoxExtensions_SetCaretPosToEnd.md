# TextBoxExtensions.SetCaretPosToEnd Method 
 

Moves the text-cursor to the last character position in the TextBox.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TextBox">DevCase.Core.Extensions.TextBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetCaretPosToEnd(
	this TextBox sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetCaretPosToEnd ( 
	sender As TextBox
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As TextBox

sender.SetCaretPosToEnd()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetCaretPosToEnd(
	TextBox^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetCaretPosToEnd : 
        sender : TextBox -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.TextBox<br />The source TextBox.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TextBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TextBox_TextBoxExtensions">TextBoxExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_TextBox">DevCase.Core.Extensions.TextBox Namespace</a><br />