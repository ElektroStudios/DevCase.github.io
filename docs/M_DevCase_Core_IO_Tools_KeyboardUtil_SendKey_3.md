# KeyboardUtil.SendKey Method (Keys, KeyBehavior)
 

Sends a keystroke to the active window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int SendKey(
	Keys key,
	KeyBehavior behavior
)
```

**VB**<br />
``` VB
Public Shared Function SendKey ( 
	key As Keys,
	behavior As KeyBehavior
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim key As Keys
Dim behavior As KeyBehavior
Dim returnValue As Integer

returnValue = KeyboardUtil.SendKey(key, behavior)
```

**C++**<br />
``` C++
public:
static int SendKey(
	Keys key, 
	KeyBehavior behavior
)
```

**F#**<br />
``` F#
static member SendKey : 
        key : Keys * 
        behavior : KeyBehavior -> int 

```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: System.Windows.Forms.Keys<br />The key to synthesize.</dd><dt>behavior</dt><dd>Type: <a href="T_DevCase_Core_IO_KeyBehavior">DevCase.Core.IO.KeyBehavior</a><br />The keystroke behavior.</dd></dl>

#### Return Value
Type: Int32<br />The function returns the number of events that it successfully inserted into the keyboard input stream. 

 If the function returns zero, the input was already blocked by another thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
SendKey(Keys.Enter, KeyBehavior.Press)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_KeyboardUtil">KeyboardUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_KeyboardUtil_SendKey">SendKey Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />