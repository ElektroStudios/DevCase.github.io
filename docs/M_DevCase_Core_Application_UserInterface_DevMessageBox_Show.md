# DevMessageBox.Show Method (String)
 

Displays a message box with specified text.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual DialogResult Show(
	string text
)
```

**VB**<br />
``` VB
Public Overridable Function Show ( 
	text As String
) As DialogResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMessageBox
Dim text As String
Dim returnValue As DialogResult

returnValue = instance.Show(text)
```

**C++**<br />
``` C++
public:
virtual DialogResult Show(
	String^ text
)
```

**F#**<br />
``` F#
abstract Show : 
        text : string -> DialogResult 
override Show : 
        text : string -> DialogResult 
```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to display in the message box.</dd></dl>

#### Return Value
Type: DialogResult<br />One of the DialogResult values.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_DevMessageBox">DevMessageBox Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_DevMessageBox_Show">Show Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />