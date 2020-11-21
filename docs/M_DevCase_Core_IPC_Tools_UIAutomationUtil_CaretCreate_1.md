# UIAutomationUtil.CaretCreate Method (Control, Int32, Int32)
 

Create a new caret for the specified control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CaretCreate(
	Control ctrl,
	int width,
	int height = 0
)
```

**VB**<br />
``` VB
Public Shared Sub CaretCreate ( 
	ctrl As Control,
	width As Integer,
	Optional height As Integer = 0
)
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim width As Integer
Dim height As Integer

UIAutomationUtil.CaretCreate(ctrl, width, height)
```

**C++**<br />
``` C++
public:
static void CaretCreate(
	Control^ ctrl, 
	int width, 
	int height = 0
)
```

**F#**<br />
``` F#
static member CaretCreate : 
        ctrl : Control * 
        width : int * 
        ?height : int 
(* Defaults:
        let _height = defaultArg height 0
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The control.</dd><dt>width</dt><dd>Type: System.Int32<br />The width of the caret cursor.</dd><dt>height (Optional)</dt><dd>Type: System.Int32<br />The width of the caret cursor.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_CaretCreate">CaretCreate Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />