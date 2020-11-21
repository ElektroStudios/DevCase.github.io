# TypeWritter.WriteAsync Method 
 

Asynchronously writes text simulating a typewritter effect.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task WriteAsync(
	CancellationToken cancellationToken,
	string text,
	int typeSpeed = 75,
	int pauseDuration = 400
)
```

**VB**<br />
``` VB
Public Shared Function WriteAsync ( 
	cancellationToken As CancellationToken,
	text As String,
	Optional typeSpeed As Integer = 75,
	Optional pauseDuration As Integer = 400
) As Task
```

**VB Usage**<br />
``` VB Usage
Dim cancellationToken As CancellationToken
Dim text As String
Dim typeSpeed As Integer
Dim pauseDuration As Integer
Dim returnValue As Task

returnValue = TypeWritter.WriteAsync(cancellationToken, 
	text, typeSpeed, pauseDuration)
```

**C++**<br />
``` C++
public:
static Task^ WriteAsync(
	CancellationToken cancellationToken, 
	String^ text, 
	int typeSpeed = 75, 
	int pauseDuration = 400
)
```

**F#**<br />
``` F#
static member WriteAsync : 
        cancellationToken : CancellationToken * 
        text : string * 
        ?typeSpeed : int * 
        ?pauseDuration : int 
(* Defaults:
        let _typeSpeed = defaultArg typeSpeed 75
        let _pauseDuration = defaultArg pauseDuration 400
*)
-> Task 

```


#### Parameters
&nbsp;<dl><dt>cancellationToken</dt><dd>Type: System.Threading.CancellationToken<br />A CancellationToken that you must use to cancel this Task.</dd><dt>text</dt><dd>Type: System.String<br />The text to type.</dd><dt>typeSpeed (Optional)</dt><dd>Type: System.Int32<br />The typying speed, in ms.</dd><dt>pauseDuration (Optional)</dt><dd>Type: System.Int32<br />The pause duration of the punctuation characters, in ms.</dd></dl>

#### Return Value
Type: Task<br />A Task object to asynchronously write text simulating a typewritter effect.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim typeCancellation As New CancellationTokenSource
Dim typeTask As Task = TypeWritter.WriteAsync(typeCancellation.Token, "Hello World!", typeSpeed:=150)
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
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter">TypeWritter Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />