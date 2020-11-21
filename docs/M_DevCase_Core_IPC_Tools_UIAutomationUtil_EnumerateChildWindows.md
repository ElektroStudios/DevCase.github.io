# UIAutomationUtil.EnumerateChildWindows Method (IntPtr)
 

Enumerates the child windows of the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<WindowInfo> EnumerateChildWindows(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
Public Shared Function EnumerateChildWindows ( 
	hWnd As IntPtr
) As IEnumerable(Of WindowInfo)
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As IEnumerable(Of WindowInfo)

returnValue = UIAutomationUtil.EnumerateChildWindows(hWnd)
```

**C++**<br />
``` C++
public:
static IEnumerable<WindowInfo^>^ EnumerateChildWindows(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
static member EnumerateChildWindows : 
        hWnd : IntPtr -> IEnumerable<WindowInfo> 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window.</dd></dl>

#### Return Value
Type: IEnumerable(<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo</a>)<br />The child windows of the specified window.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hWnd As IntPtr = Process.GetCurrentProcess().MainWindowHandle
Dim childWindows As IEnumerable(Of WindowInfo) = EnumerateChildWindows(hWnd)

For Each child As WindowInfo In childWindows
    Console.WriteLine("HWND: {0}, CLASS: {1}, TEXT: {2}", child.Hwnd.ToInt32(), child.ClassName, child.Text)
Next child
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_EnumerateChildWindows">EnumerateChildWindows Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />