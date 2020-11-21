# UIAutomationUtil.MoveWindow Method (Process, Point)
 

Moves the main window of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool MoveWindow(
	Process pr,
	Point location
)
```

**VB**<br />
``` VB
Public Shared Function MoveWindow ( 
	pr As Process,
	location As Point
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pr As Process
Dim location As Point
Dim returnValue As Boolean

returnValue = UIAutomationUtil.MoveWindow(pr, 
	location)
```

**C++**<br />
``` C++
public:
static bool MoveWindow(
	Process^ pr, 
	Point location
)
```

**F#**<br />
``` F#
static member MoveWindow : 
        pr : Process * 
        location : Point -> bool 

```


#### Parameters
&nbsp;<dl><dt>pr</dt><dd>Type: System.Diagnostics.Process<br />The process.</dd><dt>location</dt><dd>Type: System.Drawing.Point<br />The new window location.</dd></dl>

#### Return Value
Type: Boolean<br />if successful `true` (`True` in Visual Basic); `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pr As Process = Process.GetProcessesByName("notepad").FirstOrDefault()
MoveWindow(pr, New Point(0, 0))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_MoveWindow">MoveWindow Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />