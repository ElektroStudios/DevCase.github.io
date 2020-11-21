# UIAutomationUtil.SetWindowState Method (IntPtr, ProcessWindowStyle)
 

Set the visibility state of a window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SetWindowState(
	IntPtr hWnd,
	ProcessWindowStyle state
)
```

**VB**<br />
``` VB
Public Shared Function SetWindowState ( 
	hWnd As IntPtr,
	state As ProcessWindowStyle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim state As ProcessWindowStyle
Dim returnValue As Boolean

returnValue = UIAutomationUtil.SetWindowState(hWnd, 
	state)
```

**C++**<br />
``` C++
public:
static bool SetWindowState(
	IntPtr hWnd, 
	ProcessWindowStyle state
)
```

**F#**<br />
``` F#
static member SetWindowState : 
        hWnd : IntPtr * 
        state : ProcessWindowStyle -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window.</dd><dt>state</dt><dd>Type: System.Diagnostics.ProcessWindowStyle<br />The window state.</dd></dl>

#### Return Value
Type: Boolean<br />If the window was previously visible, the return value is `true` (`True` in Visual Basic). If the window was previously hidden, the return value is `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>state</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hwnd As IntPtr = Process.GetProcessesByName("notepad").First.MainWindowHandle
SetWindowState(hwnd, ProcessWindowStyle.Hidden)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_SetWindowState">SetWindowState Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />