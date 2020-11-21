# ConsoleRectangle.Equality Operator (ConsoleRectangle, ConsoleRectangle)
 

Tests whether two <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> structures have equal location, size and characters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator ==(
	ConsoleRectangle left,
	ConsoleRectangle right
)
```

**VB**<br />
``` VB
Public Shared Operator = ( 
	left As ConsoleRectangle,
	right As ConsoleRectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim left As ConsoleRectangle
Dim right As ConsoleRectangle
Dim returnValue As Boolean

returnValue = (left = right)
```

**C++**<br />
``` C++
public:
static bool operator ==(
	ConsoleRectangle left, 
	ConsoleRectangle right
)
```

**F#**<br />
``` F#
static let inline (=)
        left : ConsoleRectangle * 
        right : ConsoleRectangle  : bool
```


#### Parameters
&nbsp;<dl><dt>left</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">DevCase.Core.Application.UserInterface.ConsoleRectangle</a><br />The <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> structure that is to the left of the equality operator.</dd><dt>right</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">DevCase.Core.Application.UserInterface.ConsoleRectangle</a><br />The <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> structure that is to the right of the equality operator.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the two <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> structures have equal location, size and characters; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle Structure</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Equality">Equality Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />