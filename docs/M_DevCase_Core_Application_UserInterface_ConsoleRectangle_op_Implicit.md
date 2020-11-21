# ConsoleRectangle&nbsp;Implicit Conversion (ConsoleRectangle to Rectangle)
 

Performs an implicit conversion from <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> to Rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator Rectangle (
	ConsoleRectangle rect
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	rect As ConsoleRectangle
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim input As ConsoleRectangle
Dim output As Rectangle

output = CType(input, Rectangle)
```

**C++**<br />
``` C++
static implicit operator Rectangle (
	ConsoleRectangle rect
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>rect</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">DevCase.Core.Application.UserInterface.ConsoleRectangle</a><br />The source <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a>.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle Structure</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />