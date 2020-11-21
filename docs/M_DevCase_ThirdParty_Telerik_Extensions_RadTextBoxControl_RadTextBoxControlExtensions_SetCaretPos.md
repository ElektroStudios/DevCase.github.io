# RadTextBoxControlExtensions.SetCaretPos Method 
 

Sets the text-cursor position in the RadTextBoxControl.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl">DevCase.ThirdParty.Telerik.Extensions.RadTextBoxControl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetCaretPos(
	this RadTextBoxControl sender,
	int position
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetCaretPos ( 
	sender As RadTextBoxControl,
	position As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadTextBoxControl
Dim position As Integer

sender.SetCaretPos(position)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetCaretPos(
	RadTextBoxControl^ sender, 
	int position
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetCaretPos : 
        sender : RadTextBoxControl * 
        position : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadTextBoxControl<br />The source RadTextBoxControl.</dd><dt>position</dt><dd>Type: System.Int32<br />\[Missing <param name="position"/> documentation for "M:DevCase.ThirdParty.Telerik.Extensions.RadTextBoxControl.RadTextBoxControlExtensions.SetCaretPos(Telerik.WinControls.UI.RadTextBoxControl,System.Int32)"\]</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadTextBoxControl. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>position</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl_RadTextBoxControlExtensions">RadTextBoxControlExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl">DevCase.ThirdParty.Telerik.Extensions.RadTextBoxControl Namespace</a><br />