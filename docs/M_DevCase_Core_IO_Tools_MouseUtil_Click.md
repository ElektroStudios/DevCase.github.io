# MouseUtil.Click Method 
 

Simulates a mouse click on the active window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int Click(
	MouseButton button
)
```

**VB**<br />
``` VB
Public Shared Function Click ( 
	button As MouseButton
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim button As MouseButton
Dim returnValue As Integer

returnValue = MouseUtil.Click(button)
```

**C++**<br />
``` C++
public:
static int Click(
	MouseButton button
)
```

**F#**<br />
``` F#
static member Click : 
        button : MouseButton -> int 

```


#### Parameters
&nbsp;<dl><dt>button</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseButton">DevCase.Core.IO.MouseButton</a><br />The mouse button to simulate.</dd></dl>

#### Return Value
Type: Int32<br />The function returns the number of events that it successfully inserted into the mouse input stream. 

 If the function returns zero, the input was already blocked by another thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
Click(MouseButton.RightPress)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_MouseUtil">MouseUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />