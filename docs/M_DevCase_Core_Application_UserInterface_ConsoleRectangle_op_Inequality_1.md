# ConsoleRectangle.Inequality Operator (Rectangle, ConsoleRectangle)
 

Determine whether two Rectangle and <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> structures differ in location or size.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator !=(
	Rectangle rect,
	ConsoleRectangle consoleRect
)
```

**VB**<br />
``` VB
Public Shared Operator <> ( 
	rect As Rectangle,
	consoleRect As ConsoleRectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim rect As Rectangle
Dim consoleRect As ConsoleRectangle
Dim returnValue As Boolean

returnValue = (rect <> consoleRect)
```

**C++**<br />
``` C++
public:
static bool operator !=(
	Rectangle rect, 
	ConsoleRectangle consoleRect
)
```

**F#**<br />
``` F#
static let inline (<>)
        rect : Rectangle * 
        consoleRect : ConsoleRectangle  : bool
```


#### Parameters
&nbsp;<dl><dt>rect</dt><dd>Type: System.Drawing.Rectangle<br />The Rectangle to compare with the <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> structure.</dd><dt>consoleRect</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">DevCase.Core.Application.UserInterface.ConsoleRectangle</a><br />The <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> to compare with the Rectangle structure.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the two Rectangle and <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> structures differ in location or size; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle Structure</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Inequality">Inequality Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />