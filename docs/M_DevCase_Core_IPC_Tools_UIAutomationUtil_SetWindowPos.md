# UIAutomationUtil.SetWindowPos Method (IntPtr, Int32, Int32)
 

Sets the position of a window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SetWindowPos(
	IntPtr hWnd,
	int x,
	int y
)
```

**VB**<br />
``` VB
Public Shared Function SetWindowPos ( 
	hWnd As IntPtr,
	x As Integer,
	y As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim x As Integer
Dim y As Integer
Dim returnValue As Boolean

returnValue = UIAutomationUtil.SetWindowPos(hWnd, 
	x, y)
```

**C++**<br />
``` C++
public:
static bool SetWindowPos(
	IntPtr hWnd, 
	int x, 
	int y
)
```

**F#**<br />
``` F#
static member SetWindowPos : 
        hWnd : IntPtr * 
        x : int * 
        y : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The window handle.</dd><dt>x</dt><dd>Type: System.Int32<br />The new X coordinate.</dd><dt>y</dt><dd>Type: System.Int32<br />The new Y coordinate.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_SetWindowPos">SetWindowPos Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />