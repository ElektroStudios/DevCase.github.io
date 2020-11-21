# ConsoleRectangle&nbsp;Implicit Conversion (Rectangle to ConsoleRectangle)
 

Performs an implicit conversion from Rectangle to <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator ConsoleRectangle (
	Rectangle rect
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	rect As Rectangle
) As ConsoleRectangle
```

**VB Usage**<br />
``` VB Usage
Dim input As Rectangle
Dim output As ConsoleRectangle

output = CType(input, ConsoleRectangle)
```

**C++**<br />
``` C++
static implicit operator ConsoleRectangle (
	Rectangle rect
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>rect</dt><dd>Type: System.Drawing.Rectangle<br />The source Rectangle.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a><br />The resulting <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle Structure</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />