# TypeWritter.WriteColorAsync Method (CancellationToken, String, Char[], Int32, Int32)
 

Asynchronously writes colored text simulating a typewritter effect.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task WriteColorAsync(
	CancellationToken cancellationToken,
	string text,
	char[] delimiters,
	int typeSpeed = 75,
	int pauseDuration = 400
)
```

**VB**<br />
``` VB
Public Shared Function WriteColorAsync ( 
	cancellationToken As CancellationToken,
	text As String,
	delimiters As Char(),
	Optional typeSpeed As Integer = 75,
	Optional pauseDuration As Integer = 400
) As Task
```

**VB Usage**<br />
``` VB Usage
Dim cancellationToken As CancellationToken
Dim text As String
Dim delimiters As Char()
Dim typeSpeed As Integer
Dim pauseDuration As Integer
Dim returnValue As Task

returnValue = TypeWritter.WriteColorAsync(cancellationToken, 
	text, delimiters, typeSpeed, pauseDuration)
```

**C++**<br />
``` C++
public:
static Task^ WriteColorAsync(
	CancellationToken cancellationToken, 
	String^ text, 
	array<wchar_t>^ delimiters, 
	int typeSpeed = 75, 
	int pauseDuration = 400
)
```

**F#**<br />
``` F#
static member WriteColorAsync : 
        cancellationToken : CancellationToken * 
        text : string * 
        delimiters : char[] * 
        ?typeSpeed : int * 
        ?pauseDuration : int 
(* Defaults:
        let _typeSpeed = defaultArg typeSpeed 75
        let _pauseDuration = defaultArg pauseDuration 400
*)
-> Task 

```


#### Parameters
&nbsp;<dl><dt>cancellationToken</dt><dd>Type: System.Threading.CancellationToken<br />A CancellationToken that you must use to cancel this Task.</dd><dt>text</dt><dd>Type: System.String<br />The color-delimited text to write.</dd><dt>delimiters</dt><dd>Type: System.Char[]<br />A set of 1 or 2 delimiters to parse the color-delimited string.</dd><dt>typeSpeed (Optional)</dt><dd>Type: System.Int32<br />The typying speed, in ms.</dd><dt>pauseDuration (Optional)</dt><dd>Type: System.Int32<br />The pause duration of the punctuation characters, in ms.</dd></dl>

#### Return Value
Type: Task<br />A Task object to asynchronously write colored text simulating a typewritter effect.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim typeCancellation As New CancellationTokenSource
Dim typeTask As Task = TypeWritter.WriteColorAsync(typeCancellation.Token, "*F10*Hello *F14*World!*-F*", {"*"c}, typeSpeed:=150)
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