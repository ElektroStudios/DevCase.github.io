# GraphicalUtil.GetControlFromPoint Method (Control)
 

Gets the corresponding control (if any) that is over the specified mouse point.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Control GetControlFromPoint(
	Control container
)
```

**VB**<br />
``` VB
Public Shared Function GetControlFromPoint ( 
	container As Control
) As Control
```

**VB Usage**<br />
``` VB Usage
Dim container As Control
Dim returnValue As Control

returnValue = GraphicalUtil.GetControlFromPoint(container)
```

**C++**<br />
``` C++
public:
static Control^ GetControlFromPoint(
	Control^ container
)
```

**F#**<br />
``` F#
static member GetControlFromPoint : 
        container : Control -> Control 

```


#### Parameters
&nbsp;<dl><dt>container</dt><dd>Type: System.Windows.Forms.Control<br />The source container of controls where to search for. 

 Normally a Form, but you can specify another Control that contains a Control.ControlCollection.</dd></dl>

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