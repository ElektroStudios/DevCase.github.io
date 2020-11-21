# RichTextBoxExtensions.FindNext Method (RichTextBox, String, RichTextBoxFinds)
 

Finds the next occurrence of the specified string in the RichTextBox and selects it.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_RichTextBox">DevCase.Core.Extensions.RichTextBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool FindNext(
	this RichTextBox sender,
	string find,
	RichTextBoxFinds options
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function FindNext ( 
	sender As RichTextBox,
	find As String,
	options As RichTextBoxFinds
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As RichTextBox
Dim find As String
Dim options As RichTextBoxFinds
Dim returnValue As Boolean

returnValue = sender.FindNext(find, 
	options)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool FindNext(
	RichTextBox^ sender, 
	String^ find, 
	RichTextBoxFinds options
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FindNext : 
        sender : RichTextBox * 
        find : string * 
        options : RichTextBoxFinds -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.RichTextBox<br />The source RichTextBox.</dd><dt>find</dt><dd>Type: System.String<br />The string to find.</dd><dt>options</dt><dd>Type: System.Windows.Forms.RichTextBoxFinds<br />Specifies how a text search is carried out. 

 To pervorm an inverse search from the end of the text to the beginning, use Reverse</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the string is matched, `false` (`False` in Visual Basic) otherwise.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RichTextBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Sub Form1_Load() Handles Form1.Load

    RichTextBox1.Text = "Hello World!, Hello World!, Hello World!"

End Sub

Private Sub Button1_Click() Handles Button1.Click

   Dim result As Boolean = RichTextBox1.FindNext("Hello", RichTextBoxFinds.MatchCase)

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_RichTextBox_RichTextBoxExtensions">RichTextBoxExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_RichTextBox_RichTextBoxExtensions_FindNext">FindNext Overload</a><br /><a href="N_DevCase_Core_Extensions_RichTextBox">DevCase.Core.Extensions.RichTextBox Namespace</a><br />