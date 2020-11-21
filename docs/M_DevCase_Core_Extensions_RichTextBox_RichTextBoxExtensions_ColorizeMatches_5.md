# RichTextBoxExtensions.ColorizeMatches Method (RichTextBox, String[], Boolean, Color, Color, Font)
 

Matches all the occurrences of the specified strings in the source RichTextBox and set the foreground color, background color, and the font of any occurrence found.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_RichTextBox">DevCase.Core.Extensions.RichTextBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int ColorizeMatches(
	this RichTextBox sender,
	string[] find,
	bool ignoreCase,
	Color foreColor,
	Color backColor,
	Font font
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ColorizeMatches ( 
	sender As RichTextBox,
	find As String(),
	ignoreCase As Boolean,
	foreColor As Color,
	backColor As Color,
	font As Font
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As RichTextBox
Dim find As String()
Dim ignoreCase As Boolean
Dim foreColor As Color
Dim backColor As Color
Dim font As Font
Dim returnValue As Integer

returnValue = sender.ColorizeMatches(find, 
	ignoreCase, foreColor, backColor, 
	font)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int ColorizeMatches(
	RichTextBox^ sender, 
	array<String^>^ find, 
	bool ignoreCase, 
	Color foreColor, 
	Color backColor, 
	Font^ font
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ColorizeMatches : 
        sender : RichTextBox * 
        find : string[] * 
        ignoreCase : bool * 
        foreColor : Color * 
        backColor : Color * 
        font : Font -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.RichTextBox<br />The source RichTextBox.</dd><dt>find</dt><dd>Type: System.String[]<br />An Array containing the strings to match.</dd><dt>ignoreCase</dt><dd>Type: System.Boolean<br />Specifies how a text search is carried out.</dd><dt>foreColor</dt><dd>Type: System.Drawing.Color<br />The foreground color to set for the matched strings.</dd><dt>backColor</dt><dd>Type: System.Drawing.Color<br />The background color to set for the matched strings.</dd><dt>font</dt><dd>Type: System.Drawing.Font<br />The font to set for the matched strings.</dd></dl>

#### Return Value
Type: Int32<br />Returns the total amount of occurrences found.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RichTextBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim find As String() = {"Hello", "World"}
Dim forecolor As Color = Color.Red
Dim backcolor As Color = Color.Black
Dim font As New Font(RichTextBox1.Font.FontFamily, RichTextBox1.Font.Size, FontStyle.Italic)

RichTextBox1.ColorizeMatches(find, True, forecolor, backcolor, font)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_RichTextBox_RichTextBoxExtensions">RichTextBoxExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_RichTextBox_RichTextBoxExtensions_ColorizeMatches">ColorizeMatches Overload</a><br /><a href="N_DevCase_Core_Extensions_RichTextBox">DevCase.Core.Extensions.RichTextBox Namespace</a><br />