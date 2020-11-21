# UIAutomationUtil.SetWindowOpacity Method (IWin32Window, Int32)
 

Sets the opacity of the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SetWindowOpacity(
	IWin32Window window,
	int opacity
)
```

**VB**<br />
``` VB
Public Shared Function SetWindowOpacity ( 
	window As IWin32Window,
	opacity As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim opacity As Integer
Dim returnValue As Boolean

returnValue = UIAutomationUtil.SetWindowOpacity(window, 
	opacity)
```

**C++**<br />
``` C++
public:
static bool SetWindowOpacity(
	IWin32Window^ window, 
	int opacity
)
```

**F#**<br />
``` F#
static member SetWindowOpacity : 
        window : IWin32Window * 
        opacity : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window.</dd><dt>opacity</dt><dd>Type: System.Int32<br />The opacity. 

 The valid range is from `0` to `100`.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>opacity;Value in range of 0 to 100 is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_SetWindowOpacity">SetWindowOpacity Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />