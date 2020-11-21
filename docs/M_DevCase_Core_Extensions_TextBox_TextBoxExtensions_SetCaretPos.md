# TextBoxExtensions.SetCaretPos Method 
 

Sets the text-cursor position in the TextBox.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TextBox">DevCase.Core.Extensions.TextBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetCaretPos(
	this TextBox sender,
	int position
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetCaretPos ( 
	sender As TextBox,
	position As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As TextBox
Dim position As Integer

sender.SetCaretPos(position)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetCaretPos(
	TextBox^ sender, 
	int position
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetCaretPos : 
        sender : TextBox * 
        position : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.TextBox<br />The source TextBox.</dd><dt>position</dt><dd>Type: System.Int32<br />\[Missing <param name="position"/> documentation for "M:DevCase.Core.Extensions.TextBox.TextBoxExtensions.SetCaretPos(System.Windows.Forms.TextBox,System.Int32)"\]</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TextBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>position, 'position' must be in the range of the current text length.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TextBox_TextBoxExtensions">TextBoxExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_TextBox">DevCase.Core.Extensions.TextBox Namespace</a><br />