# ConsoleUtil.SpinCursorAsync Method 
 

Asynchronously animates the console cursor producing a spin effect.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task SpinCursorAsync(
	CancellationToken cancellationToken,
	int speed = 100
)
```

**VB**<br />
``` VB
Public Shared Function SpinCursorAsync ( 
	cancellationToken As CancellationToken,
	Optional speed As Integer = 100
) As Task
```

**VB Usage**<br />
``` VB Usage
Dim cancellationToken As CancellationToken
Dim speed As Integer
Dim returnValue As Task

returnValue = ConsoleUtil.SpinCursorAsync(cancellationToken, 
	speed)
```

**C++**<br />
``` C++
public:
static Task^ SpinCursorAsync(
	CancellationToken cancellationToken, 
	int speed = 100
)
```

**F#**<br />
``` F#
static member SpinCursorAsync : 
        cancellationToken : CancellationToken * 
        ?speed : int 
(* Defaults:
        let _speed = defaultArg speed 100
*)
-> Task 

```


#### Parameters
&nbsp;<dl><dt>cancellationToken</dt><dd>Type: System.Threading.CancellationToken<br />A CancellationToken that you must use to cancel this Task.</dd><dt>speed (Optional)</dt><dd>Type: System.Int32<br />The timeout, in milliseconds, between each movement of the animation. The spin animation has 4 movements. 

 Default value is `100`.</dd></dl>

#### Return Value
Type: Task<br />A Task object to asynchronously animate the console cursor producing a spin effect.

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.Write("Loading...")
Dim spinCancelation As New CancellationTokenSource
Dim spinTask As Task = SpinCursorAsync(spinCancelation.Token)
spinTask.Start()

' Do some work while the cursor is spinning...
For x As Integer = 0 To 50
    Thread.Sleep(100)
    Debug.WriteLine(x)
Next

' Work is done, so terminate the spin task.
spinCancelation.Cancel()
spinTask.Wait()

Console.Write(" Finished.")
Console.ReadKey()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />