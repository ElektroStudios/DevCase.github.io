# WindowInfo.ShowWindow Method 
 

Sets the specified window's show state.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void ShowWindow(
	NativeWindowState windowState
)
```

**VB**<br />
``` VB
Public Sub ShowWindow ( 
	windowState As NativeWindowState
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo
Dim windowState As NativeWindowState

instance.ShowWindow(windowState)
```

**C++**<br />
``` C++
public:
void ShowWindow(
	NativeWindowState windowState
)
```

**F#**<br />
``` F#
member ShowWindow : 
        windowState : NativeWindowState -> unit 

```


#### Parameters
&nbsp;<dl><dt>windowState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState</a><br />Specifies how the window is to be shown.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />