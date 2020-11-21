# GraphicalUtil.GetControlFromPoint Method (Form)
 

Gets the corresponding control (if any) that is over the current mouse point.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Control GetControlFromPoint(
	Form form
)
```

**VB**<br />
``` VB
Public Shared Function GetControlFromPoint ( 
	form As Form
) As Control
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim returnValue As Control

returnValue = GraphicalUtil.GetControlFromPoint(form)
```

**C++**<br />
``` C++
public:
static Control^ GetControlFromPoint(
	Form^ form
)
```

**F#**<br />
``` F#
static member GetControlFromPoint : 
        form : Form -> Control 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The source Form where to search for.</dd></dl>

#### Return Value
Type: Control<br />The resulting Control, or a null reference (`Nothing` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ctrl As Control = GetControlFromPoint(Me)
If (ctrl IsNot Nothing) Then
    Console.WriteLine(ctrl.Name)
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetControlFromPoint">GetControlFromPoint Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />