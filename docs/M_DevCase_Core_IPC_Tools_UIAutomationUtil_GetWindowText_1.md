# UIAutomationUtil.GetWindowText Method (SafeHandle)
 

Gets the text of an Edit control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetWindowText(
	SafeHandle hWnd
)
```

**VB**<br />
``` VB
Public Shared Function GetWindowText ( 
	hWnd As SafeHandle
) As String
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim returnValue As String

returnValue = UIAutomationUtil.GetWindowText(hWnd)
```

**C++**<br />
``` C++
public:
static String^ GetWindowText(
	SafeHandle^ hWnd
)
```

**F#**<br />
``` F#
static member GetWindowText : 
        hWnd : SafeHandle -> string 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A IntPtr handle to the Edit window.</dd></dl>

#### Return Value
Type: String<br />The text.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_GetWindowText">GetWindowText Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />