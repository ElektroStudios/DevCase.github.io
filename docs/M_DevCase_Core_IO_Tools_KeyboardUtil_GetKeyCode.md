# KeyboardUtil.GetKeyCode Method 
 

Translate a character to the corresponding keycode.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static short GetKeyCode(
	char c,
	IntPtr keyboardLayout = null
)
```

**VB**<br />
``` VB
Public Shared Function GetKeyCode ( 
	c As Char,
	Optional keyboardLayout As IntPtr = Nothing
) As Short
```

**VB Usage**<br />
``` VB Usage
Dim c As Char
Dim keyboardLayout As IntPtr
Dim returnValue As Short

returnValue = KeyboardUtil.GetKeyCode(c, 
	keyboardLayout)
```

**C++**<br />
``` C++
public:
static short GetKeyCode(
	wchar_t c, 
	IntPtr keyboardLayout = nullptr
)
```

**F#**<br />
``` F#
static member GetKeyCode : 
        c : char * 
        ?keyboardLayout : IntPtr 
(* Defaults:
        let _keyboardLayout = defaultArg keyboardLayout null
*)
-> int16 

```


#### Parameters
&nbsp;<dl><dt>c</dt><dd>Type: System.Char<br />The character.</dd><dt>keyboardLayout (Optional)</dt><dd>Type: System.IntPtr<br />The keyboard layout.</dd></dl>

#### Return Value
Type: Int16<br />If the function succeeds, the return value contains the keycode. 

 If the function finds no key that translates to the passed character code, the return value is `-1`.

## Examples
This is a code example. 
**VB**<br />
``` VB
MsgBox(GetKeyCode("a"c)) ' Result: 65
MsgBox(GetKeyCode("á"c)) ' Result: 65
MsgBox(GetKeyCode("á"c, IntPtr.Zero)) ' Result: 65
MsgBox(GetKeyCode("a"c, Process.GetCurrentProcess.MainWindowHandle)) ' Result: 65

Dim sb As New Global.System.Text.StringBuilder
Dim chars As Char() = "ABCDEFGHIJKLMNOPQRSTUVWXYZ ñÑçÇ áéíóú ÁÉÍÓÚ àèìòù ÀÈÌÒÙ äëïÖÜ ÄËÏÖÜ º\'¡`+´-.,ª!·$%&/()=?¿<>".ToCharArray
For Each c As Char In chars
    sb.AppendFormat("Character: {0}", CStr(c))
    sb.AppendLine()
    sb.AppendFormat("KeyCode  : {0}", CStr(DevCase.IO.Tools.Keyboard.GetKeyCode(c, IntPtr.Zero)))
    MessageBox.Show(sb.ToString())
    sb.Clear()
Next c
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_KeyboardUtil">KeyboardUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />