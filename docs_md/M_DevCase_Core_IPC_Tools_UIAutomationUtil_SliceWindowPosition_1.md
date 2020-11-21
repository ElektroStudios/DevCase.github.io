# UIAutomationUtil.SliceWindowPosition Method (IntPtr, Point)
 

Slices the position of the specified WINDOW.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SliceWindowPosition(
	IntPtr hWnd,
	Point position
)
```

**VB**<br />
``` VB
Public Shared Function SliceWindowPosition ( 
	hWnd As IntPtr,
	position As Point
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim position As Point
Dim returnValue As Boolean

returnValue = UIAutomationUtil.SliceWindowPosition(hWnd, 
	position)
```

**C++**<br />
``` C++
public:
static bool SliceWindowPosition(
	IntPtr hWnd, 
	Point position
)
```

**F#**<br />
``` F#
static member SliceWindowPosition : 
        hWnd : IntPtr * 
        position : Point -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window.</dd><dt>position</dt><dd>Type: System.Drawing.Point<br />The new window position.</dd></dl>

#### Return Value
Type: Boolean<br />if successful `true` (`True` in Visual Basic); `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hWnd as IntPtr = Process.GetProcessesByName("notepad").FirstOrDefault().MainWindowHandle
SliceWindowPosition(hWnd, New Point(+10, -100))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_SliceWindowPosition">SliceWindowPosition Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />