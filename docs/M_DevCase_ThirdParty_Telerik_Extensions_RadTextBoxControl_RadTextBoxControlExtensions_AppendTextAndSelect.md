# RadTextBoxControlExtensions.AppendTextAndSelect Method 
 

Appends the specified text to the current text of the RadTextBoxControl and selects it.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl">DevCase.ThirdParty.Telerik.Extensions.RadTextBoxControl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void AppendTextAndSelect(
	this RadTextBoxControl sender,
	string text
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub AppendTextAndSelect ( 
	sender As RadTextBoxControl,
	text As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadTextBoxControl
Dim text As String

sender.AppendTextAndSelect(text)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void AppendTextAndSelect(
	RadTextBoxControl^ sender, 
	String^ text
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AppendTextAndSelect : 
        sender : RadTextBoxControl * 
        text : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadTextBoxControl<br />The source RadTextBoxControl.</dd><dt>text</dt><dd>Type: System.String<br />The text to append.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadTextBoxControl. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl_RadTextBoxControlExtensions">RadTextBoxControlExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl">DevCase.ThirdParty.Telerik.Extensions.RadTextBoxControl Namespace</a><br />