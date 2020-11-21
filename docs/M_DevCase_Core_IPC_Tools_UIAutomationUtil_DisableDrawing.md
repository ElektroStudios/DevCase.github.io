# UIAutomationUtil.DisableDrawing Method 
 

Disables drawing on the specified window or control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DisableDrawing(
	IntPtr handle
)
```

**VB**<br />
``` VB
Public Shared Sub DisableDrawing ( 
	handle As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtrUIAutomationUtil.DisableDrawing(handle)
```

**C++**<br />
``` C++
public:
static void DisableDrawing(
	IntPtr handle
)
```

**F#**<br />
``` F#
static member DisableDrawing : 
        handle : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle to the window or control.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
DisableDrawing(TextBox1.Handle)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />