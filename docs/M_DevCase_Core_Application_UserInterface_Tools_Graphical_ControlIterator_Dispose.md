# ControlIterator.Dispose Method (IEnumerable(Control))
 

Dispose multiple Controls at once.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Dispose(
	IEnumerable<Control> ctrls
)
```

**VB**<br />
``` VB
Public Shared Function Dispose ( 
	ctrls As IEnumerable(Of Control)
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim ctrls As IEnumerable(Of Control)
Dim returnValue As Boolean

returnValue = ControlIterator.Dispose(ctrls)
```

**C++**<br />
``` C++
public:
static bool Dispose(
	IEnumerable<Control^>^ ctrls
)
```

**F#**<br />
``` F#
static member Dispose : 
        ctrls : IEnumerable<Control> -> bool 

```


#### Parameters
&nbsp;<dl><dt>ctrls</dt><dd>Type: System.Collections.Generic.IEnumerable(Control)<br />The controls to dispose.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator">ControlIterator Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Dispose">Dispose Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />