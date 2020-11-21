# ConsoleUtil.Pause Method (Keys)
 

Pause the console execution indefinitely until the specified key is pressed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Pause(
	Keys key
)
```

**VB**<br />
``` VB
Public Shared Sub Pause ( 
	key As Keys
)
```

**VB Usage**<br />
``` VB Usage
Dim key As KeysConsoleUtil.Pause(key)
```

**C++**<br />
``` C++
public:
static void Pause(
	Keys key
)
```

**F#**<br />
``` F#
static member Pause : 
        key : Keys -> unit 

```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: System.Windows.Forms.Keys<br />The key to wait for.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim key As Keys = Keys.Enter
Dim keyName As String = [Enum].GetName(GetType(Keys), key)

Console.WriteLine(String.Format("Press '{0}' key to continue...", keyName))
Pause(key)
Console.WriteLine("Well done.")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_Pause">Pause Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />