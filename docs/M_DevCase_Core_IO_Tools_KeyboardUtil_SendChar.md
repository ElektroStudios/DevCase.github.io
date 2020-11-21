# KeyboardUtil.SendChar Method 
 

Sends a character to the active window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int SendChar(
	char c
)
```

**VB**<br />
``` VB
Public Shared Function SendChar ( 
	c As Char
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim c As Char
Dim returnValue As Integer

returnValue = KeyboardUtil.SendChar(c)
```

**C++**<br />
``` C++
public:
static int SendChar(
	wchar_t c
)
```

**F#**<br />
``` F#
static member SendChar : 
        c : char -> int 

```


#### Parameters
&nbsp;<dl><dt>c</dt><dd>Type: System.Char<br />The character to send.</dd></dl>

#### Return Value
Type: Int32<br />The function returns the number of events that it successfully inserted into the keyboard input stream. 

 If the function returns zero, the input was already blocked by another thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
SendChar(Convert.ToChar(Keys.D0), KeyAction.Press)
```


## Examples
This is a code example. 
**VB**<br />
``` VB
Interaction.AppActivate(Process.GetProcessesByName("sublime_text").First.Id)

Dim c As Char = Convert.ToChar(Keys.Oemtilde) ' Ñ
Dim result As Integer = SendChar(Convert.ToChar(c.ToString().ToLower()))
MessageBox.Show(String.Format("Successfull events: {0}", CStr(result)))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_KeyboardUtil">KeyboardUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />