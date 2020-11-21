# GraphicalUtil.GetControlFromPoint Method (Form, Point)
 

Gets the corresponding control (if any) that is over the specified point.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Control GetControlFromPoint(
	Form form,
	Point pt
)
```

**VB**<br />
``` VB
Public Shared Function GetControlFromPoint ( 
	form As Form,
	pt As Point
) As Control
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim pt As Point
Dim returnValue As Control

returnValue = GraphicalUtil.GetControlFromPoint(form, 
	pt)
```

**C++**<br />
``` C++
public:
static Control^ GetControlFromPoint(
	Form^ form, 
	Point pt
)
```

**F#**<br />
``` F#
static member GetControlFromPoint : 
        form : Form * 
        pt : Point -> Control 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The source Form where to search for.</dd><dt>pt</dt><dd>Type: System.Drawing.Point<br />The mouse point, in non-relative screen coordinates.</dd></dl>

#### Return Value
Type: Control<br />The resulting Control, or a null reference (`Nothing` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ctrl As Control = GetControlFromPoint(Me, Cursor.Position)
If (ctrl IsNot Nothing) Then
    Console.WriteLine(ctrl.Name)
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetControlFromPoint">GetControlFromPoint Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />