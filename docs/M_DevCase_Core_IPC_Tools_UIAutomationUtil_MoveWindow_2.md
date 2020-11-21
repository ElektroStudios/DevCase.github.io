# UIAutomationUtil.MoveWindow Method (IWin32Window, Point)
 

Moves the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool MoveWindow(
	IWin32Window window,
	Point location
)
```

**VB**<br />
``` VB
Public Shared Function MoveWindow ( 
	window As IWin32Window,
	location As Point
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim location As Point
Dim returnValue As Boolean

returnValue = UIAutomationUtil.MoveWindow(window, 
	location)
```

**C++**<br />
``` C++
public:
static bool MoveWindow(
	IWin32Window^ window, 
	Point location
)
```

**F#**<br />
``` F#
static member MoveWindow : 
        window : IWin32Window * 
        location : Point -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window.</dd><dt>location</dt><dd>Type: System.Drawing.Point<br />\[Missing <param name="location"/> documentation for "M:DevCase.Core.IPC.Tools.UIAutomationUtil.MoveWindow(System.Windows.Forms.IWin32Window,System.Drawing.Point)"\]</dd></dl>

#### Return Value
Type: Boolean<br />if successful `true` (`True` in Visual Basic); `false` (`False` in Visual Basic) otherwise

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim window As IWin32Window = NativeWindow.FromHandle(Process.GetProcessesByName("notepad").FirstOrDefault().MainWindowHandle)
MoveWindow(window, New Point(0, 0))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_MoveWindow">MoveWindow Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />