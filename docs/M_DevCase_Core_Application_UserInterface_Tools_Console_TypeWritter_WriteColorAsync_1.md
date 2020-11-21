# TypeWritter.WriteColorAsync Method (CancellationToken, String, ConsoleColor, ConsoleColor, Int32, Int32)
 

Asynchronously writes colored text simulating a typewritter effect.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task WriteColorAsync(
	CancellationToken cancellationToken,
	string text,
	ConsoleColor foreColor,
	ConsoleColor backColor,
	int typeSpeed = 75,
	int pauseDuration = 400
)
```

**VB**<br />
``` VB
Public Shared Function WriteColorAsync ( 
	cancellationToken As CancellationToken,
	text As String,
	foreColor As ConsoleColor,
	backColor As ConsoleColor,
	Optional typeSpeed As Integer = 75,
	Optional pauseDuration As Integer = 400
) As Task
```

**VB Usage**<br />
``` VB Usage
Dim cancellationToken As CancellationToken
Dim text As String
Dim foreColor As ConsoleColor
Dim backColor As ConsoleColor
Dim typeSpeed As Integer
Dim pauseDuration As Integer
Dim returnValue As Task

returnValue = TypeWritter.WriteColorAsync(cancellationToken, 
	text, foreColor, backColor, typeSpeed, 
	pauseDuration)
```

**C++**<br />
``` C++
public:
static Task^ WriteColorAsync(
	CancellationToken cancellationToken, 
	String^ text, 
	ConsoleColor foreColor, 
	ConsoleColor backColor, 
	int typeSpeed = 75, 
	int pauseDuration = 400
)
```

**F#**<br />
``` F#
static member WriteColorAsync : 
        cancellationToken : CancellationToken * 
        text : string * 
        foreColor : ConsoleColor * 
        backColor : ConsoleColor * 
        ?typeSpeed : int * 
        ?pauseDuration : int 
(* Defaults:
        let _typeSpeed = defaultArg typeSpeed 75
        let _pauseDuration = defaultArg pauseDuration 400
*)
-> Task 

```


#### Parameters
&nbsp;<dl><dt>cancellationToken</dt><dd>Type: System.Threading.CancellationToken<br />A CancellationToken that you must use to cancel this Task.</dd><dt>text</dt><dd>Type: System.String<br />The text to write.</dd><dt>foreColor</dt><dd>Type: System.ConsoleColor<br />The text color.</dd><dt>backColor</dt><dd>Type: System.ConsoleColor<br />The background color.</dd><dt>typeSpeed (Optional)</dt><dd>Type: System.Int32<br />The typying speed, in ms.</dd><dt>pauseDuration (Optional)</dt><dd>Type: System.Int32<br />The pause duration of the punctuation characters, in ms.</dd></dl>

#### Return Value
Type: Task<br />A Task object to asynchronously write colored text simulating a typewritter effect.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim typeCancellation As New CancellationTokenSource
Dim typeTask As Task = TypeWritter.WriteColorAsync(typeCancellation.Token, " Hello World! ", ConsoleColor.Blue, ConsoleColor.White, typeSpeed:=150)
typeTask.Start()

' Do some work while typewritting...
For x As Integer = 0 To 10
    Thread.Sleep(100)
    Debug.WriteLine(x)
Next

'' Work is done, and here you can cancel the task as you like...
' typeCancellation.Cancel()
' typeTask.Wait()
' Console.Write(" Finished.")
Console.ReadKey()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter">TypeWritter Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColorAsync">WriteColorAsync Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />