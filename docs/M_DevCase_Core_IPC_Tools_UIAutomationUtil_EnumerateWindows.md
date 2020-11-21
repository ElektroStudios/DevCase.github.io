# UIAutomationUtil.EnumerateWindows Method 
 

Enumerates the top-level windows on the screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<WindowInfo> EnumerateWindows()
```

**VB**<br />
``` VB
Public Shared Function EnumerateWindows As IEnumerable(Of WindowInfo)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IEnumerable(Of WindowInfo)

returnValue = UIAutomationUtil.EnumerateWindows()
```

**C++**<br />
``` C++
public:
static IEnumerable<WindowInfo^>^ EnumerateWindows()
```

**F#**<br />
``` F#
static member EnumerateWindows : unit -> IEnumerable<WindowInfo> 

```


#### Return Value
Type: IEnumerable(<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo</a>)<br />The top-level windows.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim windows As IEnumerable(Of WindowInfo) =EnumerateWindows()

For Each window As WindowInfo In windows
    Console.WriteLine("HWND: {0}, CLASS: {1}, TEXT: {2}", window.Hwnd.ToInt32(), window.ClassName, window.Text)
Next window
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />