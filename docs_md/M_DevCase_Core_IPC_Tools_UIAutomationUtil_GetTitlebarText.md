# UIAutomationUtil.GetTitlebarText Method 
 

Gets the titlebar's text of the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetTitlebarText(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
Public Shared Function GetTitlebarText ( 
	hWnd As IntPtr
) As String
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As String

returnValue = UIAutomationUtil.GetTitlebarText(hWnd)
```

**C++**<br />
``` C++
public:
static String^ GetTitlebarText(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
static member GetTitlebarText : 
        hWnd : IntPtr -> string 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />An IntPtr to the window.</dd></dl>

#### Return Value
Type: String<br />The titlebar's text of the target window.

## Examples
This is a code example. 
**VB**<br />
``` VB
MessageBox.Show(GetTitlebarText(Process.GetCurrentProcess.MainWindowHandle))
MessageBox.Show(GetTitlebarText(Process.GetProcessesByName("notepad").First.MainWindowHandle))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />