# KeyboardUtil.SendKey Method (IntPtr, Keys, KeyBehavior)
 

Sends a keystroke to the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SendKey(
	IntPtr hWnd,
	Keys key,
	KeyBehavior behavior
)
```

**VB**<br />
``` VB
Public Shared Function SendKey ( 
	hWnd As IntPtr,
	key As Keys,
	behavior As KeyBehavior
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim key As Keys
Dim behavior As KeyBehavior
Dim returnValue As Boolean

returnValue = KeyboardUtil.SendKey(hWnd, 
	key, behavior)
```

**C++**<br />
``` C++
public:
static bool SendKey(
	IntPtr hWnd, 
	Keys key, 
	KeyBehavior behavior
)
```

**F#**<br />
``` F#
static member SendKey : 
        hWnd : IntPtr * 
        key : Keys * 
        behavior : KeyBehavior -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the target window.</dd><dt>key</dt><dd>Type: System.Windows.Forms.Keys<br />The key to synthesize.</dd><dt>behavior</dt><dd>Type: <a href="T_DevCase_Core_IO_KeyBehavior">DevCase.Core.IO.KeyBehavior</a><br />The keystroke behavior.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hWnd As IntPtr = Process.GetCurrentProcess().MainWindowHandle
SendKey(hWnd, VirtualKeys.F1, KeyBehavior.Press)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_KeyboardUtil">KeyboardUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_KeyboardUtil_SendKey">SendKey Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />