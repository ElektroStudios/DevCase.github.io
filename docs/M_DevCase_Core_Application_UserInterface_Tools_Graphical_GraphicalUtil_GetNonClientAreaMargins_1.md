# GraphicalUtil.GetNonClientAreaMargins Method (Form)
 

Gets the non-client area margins of a Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static NonClientAreaMargins GetNonClientAreaMargins(
	Form form
)
```

**VB**<br />
``` VB
Public Shared Function GetNonClientAreaMargins ( 
	form As Form
) As NonClientAreaMargins
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim returnValue As NonClientAreaMargins

returnValue = GraphicalUtil.GetNonClientAreaMargins(form)
```

**C++**<br />
``` C++
public:
static NonClientAreaMargins GetNonClientAreaMargins(
	Form^ form
)
```

**F#**<br />
``` F#
static member GetNonClientAreaMargins : 
        form : Form -> NonClientAreaMargins 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The Form.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_UserInterface_NonClientAreaMargins">NonClientAreaMargins</a><br />A <a href="T_DevCase_Core_Application_UserInterface_NonClientAreaMargins">NonClientAreaMargins</a> structure that contains the margins size.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim margins As NonClientAreaMargins = GetNonClientAreaMargins(Me)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetNonClientAreaMargins">GetNonClientAreaMargins Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />