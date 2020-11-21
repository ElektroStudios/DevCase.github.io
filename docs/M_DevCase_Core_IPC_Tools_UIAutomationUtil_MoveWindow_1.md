# UIAutomationUtil.MoveWindow Method (IntPtr, Point)
 

Moves the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool MoveWindow(
	IntPtr hWnd,
	Point location
)
```

**VB**<br />
``` VB
Public Shared Function MoveWindow ( 
	hWnd As IntPtr,
	location As Point
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim location As Point
Dim returnValue As Boolean

returnValue = UIAutomationUtil.MoveWindow(hWnd, 
	location)
```

**C++**<br />
``` C++
public:
static bool MoveWindow(
	IntPtr hWnd, 
	Point location
)
```

**F#**<br />
``` F#
static member MoveWindow : 
        hWnd : IntPtr * 
        location : Point -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window.</dd><dt>location</dt><dd>Type: System.Drawing.Point<br />The new window location.</dd></dl>

#### Return Value
Type: Boolean<br />if successful `true` (`True` in Visual Basic); `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hWnd as IntPtr = Process.GetProcessesByName("notepad").FirstOrDefault().MainWindowHandle
MoveWindow(hWnd, New Point(0, 0))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_MoveWindow">MoveWindow Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />