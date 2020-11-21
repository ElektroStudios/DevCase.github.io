# DevMessageBox.Show Method (String, String, MessageBoxButtons, MessageBoxIcon, MessageBoxDefaultButton, MessageBoxOptions, Boolean)
 

Displays a message box with the specified text, caption, buttons, icon, default button, options, and Help button.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual DialogResult Show(
	string text,
	string caption,
	MessageBoxButtons buttons,
	MessageBoxIcon icon,
	MessageBoxDefaultButton defaultButton,
	MessageBoxOptions options,
	bool displayHelpButton
)
```

**VB**<br />
``` VB
Public Overridable Function Show ( 
	text As String,
	caption As String,
	buttons As MessageBoxButtons,
	icon As MessageBoxIcon,
	defaultButton As MessageBoxDefaultButton,
	options As MessageBoxOptions,
	displayHelpButton As Boolean
) As DialogResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMessageBox
Dim text As String
Dim caption As String
Dim buttons As MessageBoxButtons
Dim icon As MessageBoxIcon
Dim defaultButton As MessageBoxDefaultButton
Dim options As MessageBoxOptions
Dim displayHelpButton As Boolean
Dim returnValue As DialogResult

returnValue = instance.Show(text, caption, 
	buttons, icon, defaultButton, options, 
	displayHelpButton)
```

**C++**<br />
``` C++
public:
virtual DialogResult Show(
	String^ text, 
	String^ caption, 
	MessageBoxButtons buttons, 
	MessageBoxIcon icon, 
	MessageBoxDefaultButton defaultButton, 
	MessageBoxOptions options, 
	bool displayHelpButton
)
```

**F#**<br />
``` F#
abstract Show : 
        text : string * 
        caption : string * 
        buttons : MessageBoxButtons * 
        icon : MessageBoxIcon * 
        defaultButton : MessageBoxDefaultButton * 
        options : MessageBoxOptions * 
        displayHelpButton : bool -> DialogResult 
override Show : 
        text : string * 
        caption : string * 
        buttons : MessageBoxButtons * 
        icon : MessageBoxIcon * 
        defaultButton : MessageBoxDefaultButton * 
        options : MessageBoxOptions * 
        displayHelpButton : bool -> DialogResult 
```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to display in the message box.</dd><dt>caption</dt><dd>Type: System.String<br />The text to display in the title bar of the message box.</dd><dt>buttons</dt><dd>Type: System.Windows.Forms.MessageBoxButtons<br />One of the MessageBoxButtons values that specifies which buttons to display in the message box.</dd><dt>icon</dt><dd>Type: System.Windows.Forms.MessageBoxIcon<br />One of the MessageBoxIcon values that specifies which icon to display in the message box.</dd><dt>defaultButton</dt><dd>Type: System.Windows.Forms.MessageBoxDefaultButton<br />One of the MessageBoxDefaultButton values that specifies the default button for the message box.</dd><dt>options</dt><dd>Type: System.Windows.Forms.MessageBoxOptions<br />One of the MessageBoxOptions values that specifies which display and association options will be used for the message box. 

 You may pass in 0 if you wish to use the defaults.</dd><dt>displayHelpButton</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to show the Help button; otherwise, false. The default is `false` (`False` in Visual Basic).</dd></dl>

#### Return Value
Type: DialogResult<br />One of the DialogResult values.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_DevMessageBox">DevMessageBox Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_DevMessageBox_Show">Show Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />