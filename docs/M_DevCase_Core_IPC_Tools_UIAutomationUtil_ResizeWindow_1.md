# UIAutomationUtil.ResizeWindow Method (IntPtr, Size)
 

Resizes the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ResizeWindow(
	IntPtr hWnd,
	Size size
)
```

**VB**<br />
``` VB
Public Shared Function ResizeWindow ( 
	hWnd As IntPtr,
	size As Size
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim size As Size
Dim returnValue As Boolean

returnValue = UIAutomationUtil.ResizeWindow(hWnd, 
	size)
```

**C++**<br />
``` C++
public:
static bool ResizeWindow(
	IntPtr hWnd, 
	Size size
)
```

**F#**<br />
``` F#
static member ResizeWindow : 
        hWnd : IntPtr * 
        size : Size -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window.</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />The new window size.</dd></dl>

#### Return Value
Type: Boolean<br />if successful `true` (`True` in Visual Basic); `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hWnd as IntPtr = Process.GetProcessesByName("notepad").FirstOrDefault().MainWindowHandle
ResizeWindow(hWnd, New Size(640, 480))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_ResizeWindow">ResizeWindow Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />