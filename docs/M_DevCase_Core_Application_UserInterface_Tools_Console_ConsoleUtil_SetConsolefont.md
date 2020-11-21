# ConsoleUtil.SetConsolefont Method 
 

Sets the text font for the console attached to the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void SetConsolefont(
	string faceName,
	bool bold = false
)
```

**VB**<br />
``` VB
Public Sub SetConsolefont ( 
	faceName As String,
	Optional bold As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleUtil
Dim faceName As String
Dim bold As Boolean

instance.SetConsolefont(faceName, bold)
```

**C++**<br />
``` C++
public:
void SetConsolefont(
	String^ faceName, 
	bool bold = false
)
```

**F#**<br />
``` F#
member SetConsolefont : 
        faceName : string * 
        ?bold : bool 
(* Defaults:
        let _bold = defaultArg bold false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>faceName</dt><dd>Type: System.String<br />The name of the font typeface (such as Arial, Courier or Consolas).</dd><dt>bold (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), use the bold font; otherwise, use the normal font. 

 Default value is `false` (`False` in Visual Basic).</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />