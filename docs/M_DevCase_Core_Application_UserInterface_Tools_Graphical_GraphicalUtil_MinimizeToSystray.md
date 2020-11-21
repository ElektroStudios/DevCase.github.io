# GraphicalUtil.MinimizeToSystray Method 
 

Minimizes the specified Form to system-tray.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void MinimizeToSystray(
	Form form,
	NotifyIcon ntfy
)
```

**VB**<br />
``` VB
Public Shared Sub MinimizeToSystray ( 
	form As Form,
	ntfy As NotifyIcon
)
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim ntfy As NotifyIconGraphicalUtil.MinimizeToSystray(form, ntfy)
```

**C++**<br />
``` C++
public:
static void MinimizeToSystray(
	Form^ form, 
	NotifyIcon^ ntfy
)
```

**F#**<br />
``` F#
static member MinimizeToSystray : 
        form : Form * 
        ntfy : NotifyIcon -> unit 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The target Form to minimize.</dd><dt>ntfy</dt><dd>Type: System.Windows.Forms.NotifyIcon<br />The NotifyIcon.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>ntfy</td></tr><tr><td>ArgumentException</td><td>The NotifyIcon doesn't have an icon.;ntfy or The Form is not visible.;form</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />