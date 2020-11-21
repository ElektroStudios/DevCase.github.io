# KeyboardUtil.SendString Method 
 

Sends a string to the active window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int SendString(
	string str
)
```

**VB**<br />
``` VB
Public Shared Function SendString ( 
	str As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim returnValue As Integer

returnValue = KeyboardUtil.SendString(str)
```

**C++**<br />
``` C++
public:
static int SendString(
	String^ str
)
```

**F#**<br />
``` F#
static member SendString : 
        str : string -> int 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to send.</dd></dl>

#### Return Value
Type: Int32<br />The function returns the number of events that it successfully inserted into the keyboard input stream. 

 If the function returns zero, the input was already blocked by another thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
SendString("Hello World!")
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_KeyboardUtil">KeyboardUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />