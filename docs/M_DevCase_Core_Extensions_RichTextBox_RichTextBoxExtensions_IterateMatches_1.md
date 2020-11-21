# RichTextBoxExtensions.IterateMatches Method (RichTextBox, Regex[], Action(RichTextBox, Match))
 

Matches all the occurrences of the specified regular expressions in the source RichTextBox and invokes the specified action for any occurrence found.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_RichTextBox">DevCase.Core.Extensions.RichTextBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void IterateMatches(
	this RichTextBox sender,
	Regex[] find,
	Action<RichTextBox, Match> action
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub IterateMatches ( 
	sender As RichTextBox,
	find As Regex(),
	action As Action(Of RichTextBox, Match)
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RichTextBox
Dim find As Regex()
Dim action As Action(Of RichTextBox, Match)

sender.IterateMatches(find, action)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void IterateMatches(
	RichTextBox^ sender, 
	array<Regex^>^ find, 
	Action<RichTextBox^, Match^>^ action
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IterateMatches : 
        sender : RichTextBox * 
        find : Regex[] * 
        action : Action<RichTextBox, Match> -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.RichTextBox<br />The source RichTextBox.</dd><dt>find</dt><dd>Type: System.Text.RegularExpressions.Regex[]<br />An Array containing the regular expressions to match.</dd><dt>action</dt><dd>Type: System.Action(RichTextBox, Match)<br />An <a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action</a> to perform on each match.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RichTextBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rgx1 As New Regex("[0-9]", RegexOptions.None)
Dim rgx2 As New Regex("[a-z]", RegexOptions.None)
Dim forecolor As Color = Color.Red
Dim backcolor As Color = Color.Black
Dim font As New Font(RichTextBox1.Font.FontFamily, RichTextBox1.Font.Size, FontStyle.Italic)

Dim action As New Action(Of RichTextBox, Match)(
    Sub(rtb As RichTextBox, m As Match)
        With rtb
            .Select(m.Index, m.Length)
            .SelectionColor = forecolor
            .SelectionBackColor = backcolor
            .SelectionFont = font
        End With
    End Sub)

RichTextBox1.IterateMatches({rgx1, rgx2}, action)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_RichTextBox_RichTextBoxExtensions">RichTextBoxExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_RichTextBox_RichTextBoxExtensions_IterateMatches">IterateMatches Overload</a><br /><a href="N_DevCase_Core_Extensions_RichTextBox">DevCase.Core.Extensions.RichTextBox Namespace</a><br />