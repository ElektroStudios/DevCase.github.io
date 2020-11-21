# ConsoleUtil.SpinCursor Method 
 

Animates the console cursor producing a spin effect.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SpinCursor(
	int repeat,
	int speed = 100
)
```

**VB**<br />
``` VB
Public Shared Sub SpinCursor ( 
	repeat As Integer,
	Optional speed As Integer = 100
)
```

**VB Usage**<br />
``` VB Usage
Dim repeat As Integer
Dim speed As Integer

ConsoleUtil.SpinCursor(repeat, speed)
```

**C++**<br />
``` C++
public:
static void SpinCursor(
	int repeat, 
	int speed = 100
)
```

**F#**<br />
``` F#
static member SpinCursor : 
        repeat : int * 
        ?speed : int 
(* Defaults:
        let _speed = defaultArg speed 100
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>repeat</dt><dd>Type: System.Int32<br />The amount of times to repeat the spin animation.</dd><dt>speed (Optional)</dt><dd>Type: System.Int32<br />The timeout, in milliseconds, between each movement of the animation. The spin animation has 4 movements. 

 Default value is `100`.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.Write("Loading...")
SpinCursor(repeat:=10)
Console.Write(" Finished.")
Console.ReadKey()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />