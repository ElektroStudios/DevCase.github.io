# WindowInfo Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public WindowInfo(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
Public Sub New ( 
	hWnd As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr

Dim instance As New WindowInfo(hWnd)
```

**C++**<br />
``` C++
public:
WindowInfo(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
new : 
        hWnd : IntPtr -> WindowInfo
```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>hWnd</td></tr><tr><td>ArgumentException</td><td>The specified handle does not point to a valid window</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />