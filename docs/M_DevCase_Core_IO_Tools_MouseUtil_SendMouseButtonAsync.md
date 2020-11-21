# MouseUtil.SendMouseButtonAsync Method (IntPtr, MouseButton)
 

Asynchronouslly sends a mouse button click to the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SendMouseButtonAsync(
	IntPtr hWnd,
	MouseButton button
)
```

**VB**<br />
``` VB
Public Shared Function SendMouseButtonAsync ( 
	hWnd As IntPtr,
	button As MouseButton
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim button As MouseButton
Dim returnValue As Boolean

returnValue = MouseUtil.SendMouseButtonAsync(hWnd, 
	button)
```

**C++**<br />
``` C++
public:
static bool SendMouseButtonAsync(
	IntPtr hWnd, 
	MouseButton button
)
```

**F#**<br />
``` F#
static member SendMouseButtonAsync : 
        hWnd : IntPtr * 
        button : MouseButton -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the target window.</dd><dt>button</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseButton">DevCase.Core.IO.MouseButton</a><br />The mouse button to simulate.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_MouseUtil">MouseUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_MouseUtil_SendMouseButtonAsync">SendMouseButtonAsync Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />