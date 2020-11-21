# FormDragger.RemoveForm Method 
 

Removes the specified Form from the draggable elements.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void RemoveForm(
	Form form
)
```

**VB**<br />
``` VB
Public Sub RemoveForm ( 
	form As Form
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormDragger
Dim form As Form

instance.RemoveForm(form)
```

**C++**<br />
``` C++
public:
void RemoveForm(
	Form^ form
)
```

**F#**<br />
``` F#
member RemoveForm : 
        form : Form -> unit 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The Form.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The specified form is not found.;form</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />