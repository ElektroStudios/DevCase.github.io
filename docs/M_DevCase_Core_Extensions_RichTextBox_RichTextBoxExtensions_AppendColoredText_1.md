# RichTextBoxExtensions.AppendColoredText Method (RichTextBox, String, Color, Color)
 

Appends colored text to the current text of the RichTextBox.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_RichTextBox">DevCase.Core.Extensions.RichTextBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void AppendColoredText(
	this RichTextBox sender,
	string text,
	Color foreColor,
	Color backColor
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub AppendColoredText ( 
	sender As RichTextBox,
	text As String,
	foreColor As Color,
	backColor As Color
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RichTextBox
Dim text As String
Dim foreColor As Color
Dim backColor As Color

sender.AppendColoredText(text, foreColor, 
	backColor)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void AppendColoredText(
	RichTextBox^ sender, 
	String^ text, 
	Color foreColor, 
	Color backColor
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AppendColoredText : 
        sender : RichTextBox * 
        text : string * 
        foreColor : Color * 
        backColor : Color -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.RichTextBox<br />The source RichTextBox.</dd><dt>text</dt><dd>Type: System.String<br />The text to append.</dd><dt>foreColor</dt><dd>Type: System.Drawing.Color<br />The text color.</dd><dt>backColor</dt><dd>Type: System.Drawing.Color<br />The foregorund color of the text.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RichTextBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_RichTextBox_RichTextBoxExtensions">RichTextBoxExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_RichTextBox_RichTextBoxExtensions_AppendColoredText">AppendColoredText Overload</a><br /><a href="N_DevCase_Core_Extensions_RichTextBox">DevCase.Core.Extensions.RichTextBox Namespace</a><br />