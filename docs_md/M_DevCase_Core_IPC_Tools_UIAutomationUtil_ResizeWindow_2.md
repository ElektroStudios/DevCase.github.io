# UIAutomationUtil.ResizeWindow Method (IWin32Window, Size)
 

Resizes the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ResizeWindow(
	IWin32Window window,
	Size size
)
```

**VB**<br />
``` VB
Public Shared Function ResizeWindow ( 
	window As IWin32Window,
	size As Size
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim size As Size
Dim returnValue As Boolean

returnValue = UIAutomationUtil.ResizeWindow(window, 
	size)
```

**C++**<br />
``` C++
public:
static bool ResizeWindow(
	IWin32Window^ window, 
	Size size
)
```

**F#**<br />
``` F#
static member ResizeWindow : 
        window : IWin32Window * 
        size : Size -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window.</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />The new window size.</dd></dl>

#### Return Value
Type: Boolean<br />if successful `true` (`True` in Visual Basic); `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim window As IWin32Window = NativeWindow.FromHandle(Process.GetProcessesByName("notepad").FirstOrDefault().MainWindowHandle)
ResizeWindow(window, New Size(640, 480))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_ResizeWindow">ResizeWindow Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />