# WindowInfo.SetForegroundWindow Method 
 

Brings the thread that created this window into the foreground, and activates the window. 

 Keyboard input is directed to the window, and various visual cues are changed for the user.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void SetForegroundWindow()
```

**VB**<br />
``` VB
Public Sub SetForegroundWindow
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo

instance.SetForegroundWindow()
```

**C++**<br />
``` C++
public:
void SetForegroundWindow()
```

**F#**<br />
``` F#
member SetForegroundWindow : unit -> unit 

```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />