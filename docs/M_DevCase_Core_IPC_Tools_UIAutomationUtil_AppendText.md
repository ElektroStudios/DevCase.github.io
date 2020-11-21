# UIAutomationUtil.AppendText Method 
 

Appends text at the end of an Edit control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AppendText(
	IntPtr hWnd,
	string text
)
```

**VB**<br />
``` VB
Public Shared Function AppendText ( 
	hWnd As IntPtr,
	text As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim text As String
Dim returnValue As Boolean

returnValue = UIAutomationUtil.AppendText(hWnd, 
	text)
```

**C++**<br />
``` C++
public:
static bool AppendText(
	IntPtr hWnd, 
	String^ text
)
```

**F#**<br />
``` F#
static member AppendText : 
        hWnd : IntPtr * 
        text : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A IntPtr handle to the Edit window.</dd><dt>text</dt><dd>Type: System.String<br />The text to append.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `true` (`True` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />