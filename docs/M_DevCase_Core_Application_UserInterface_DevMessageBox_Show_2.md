# DevMessageBox.Show Method (String, String, MessageBoxButtons)
 

Displays a message box with specified text, caption, and buttons.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual DialogResult Show(
	string text,
	string caption,
	MessageBoxButtons buttons
)
```

**VB**<br />
``` VB
Public Overridable Function Show ( 
	text As String,
	caption As String,
	buttons As MessageBoxButtons
) As DialogResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMessageBox
Dim text As String
Dim caption As String
Dim buttons As MessageBoxButtons
Dim returnValue As DialogResult

returnValue = instance.Show(text, caption, 
	buttons)
```

**C++**<br />
``` C++
public:
virtual DialogResult Show(
	String^ text, 
	String^ caption, 
	MessageBoxButtons buttons
)
```

**F#**<br />
``` F#
abstract Show : 
        text : string * 
        caption : string * 
        buttons : MessageBoxButtons -> DialogResult 
override Show : 
        text : string * 
        caption : string * 
        buttons : MessageBoxButtons -> DialogResult 
```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to display in the message box.</dd><dt>caption</dt><dd>Type: System.String<br />The text to display in the title bar of the message box.</dd><dt>buttons</dt><dd>Type: System.Windows.Forms.MessageBoxButtons<br />One of the MessageBoxButtons values that specifies which buttons to display in the message box.</dd></dl>

#### Return Value
Type: DialogResult<br />One of the DialogResult values.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_DevMessageBox">DevMessageBox Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_DevMessageBox_Show">Show Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />