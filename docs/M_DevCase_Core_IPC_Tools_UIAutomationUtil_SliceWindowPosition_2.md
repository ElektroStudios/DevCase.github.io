# UIAutomationUtil.SliceWindowPosition Method (IWin32Window, Point)
 

Slices the position of the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SliceWindowPosition(
	IWin32Window window,
	Point location
)
```

**VB**<br />
``` VB
Public Shared Function SliceWindowPosition ( 
	window As IWin32Window,
	location As Point
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim location As Point
Dim returnValue As Boolean

returnValue = UIAutomationUtil.SliceWindowPosition(window, 
	location)
```

**C++**<br />
``` C++
public:
static bool SliceWindowPosition(
	IWin32Window^ window, 
	Point location
)
```

**F#**<br />
``` F#
static member SliceWindowPosition : 
        window : IWin32Window * 
        location : Point -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window.</dd><dt>location</dt><dd>Type: System.Drawing.Point<br />The new window location.</dd></dl>

#### Return Value
Type: Boolean<br />if successful `true` (`True` in Visual Basic); `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim window As IWin32Window = NativeWindow.FromHandle(Process.GetProcessesByName("notepad").FirstOrDefault().MainWindowHandle)
SliceWindowPosition(window, New Point(+10, -100))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_SliceWindowPosition">SliceWindowPosition Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />