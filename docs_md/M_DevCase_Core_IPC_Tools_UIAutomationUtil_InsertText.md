# UIAutomationUtil.InsertText Method 
 

Inserts text at the specified position of an Edit control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool InsertText(
	IntPtr hWnd,
	int position,
	string text
)
```

**VB**<br />
``` VB
Public Shared Function InsertText ( 
	hWnd As IntPtr,
	position As Integer,
	text As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim position As Integer
Dim text As String
Dim returnValue As Boolean

returnValue = UIAutomationUtil.InsertText(hWnd, 
	position, text)
```

**C++**<br />
``` C++
public:
static bool InsertText(
	IntPtr hWnd, 
	int position, 
	String^ text
)
```

**F#**<br />
``` F#
static member InsertText : 
        hWnd : IntPtr * 
        position : int * 
        text : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A IntPtr handle to the Edit window.</dd><dt>position</dt><dd>Type: System.Int32<br />The character position where to insert the text.</dd><dt>text</dt><dd>Type: System.String<br />The text to insert.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `true` (`True` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />