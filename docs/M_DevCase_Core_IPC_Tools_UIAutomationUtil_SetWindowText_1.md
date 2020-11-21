# UIAutomationUtil.SetWindowText Method (SafeHandle, String)
 

Sets the text of an Edit control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SetWindowText(
	SafeHandle hWnd,
	string text
)
```

**VB**<br />
``` VB
Public Shared Function SetWindowText ( 
	hWnd As SafeHandle,
	text As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim text As String
Dim returnValue As Boolean

returnValue = UIAutomationUtil.SetWindowText(hWnd, 
	text)
```

**C++**<br />
``` C++
public:
static bool SetWindowText(
	SafeHandle^ hWnd, 
	String^ text
)
```

**F#**<br />
``` F#
static member SetWindowText : 
        hWnd : SafeHandle * 
        text : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A IntPtr handle to the Edit window.</dd><dt>text</dt><dd>Type: System.String<br />The text.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `true` (`True` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_SetWindowText">SetWindowText Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />