# ConsoleUtil.ConsoleTextBlink Method (Point, Int32, TimeSpan, Int32)
 

Blinks the specified text for the specified amount of times on the current attached console window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static CancellationTokenSource ConsoleTextBlink(
	Point position,
	int length,
	TimeSpan interval,
	int count
)
```

**VB**<br />
``` VB
Public Shared Function ConsoleTextBlink ( 
	position As Point,
	length As Integer,
	interval As TimeSpan,
	count As Integer
) As CancellationTokenSource
```

**VB Usage**<br />
``` VB Usage
Dim position As Point
Dim length As Integer
Dim interval As TimeSpan
Dim count As Integer
Dim returnValue As CancellationTokenSource

returnValue = ConsoleUtil.ConsoleTextBlink(position, 
	length, interval, count)
```

**C++**<br />
``` C++
public:
static CancellationTokenSource^ ConsoleTextBlink(
	Point position, 
	int length, 
	TimeSpan interval, 
	int count
)
```

**F#**<br />
``` F#
static member ConsoleTextBlink : 
        position : Point * 
        length : int * 
        interval : TimeSpan * 
        count : int -> CancellationTokenSource 

```


#### Parameters
&nbsp;<dl><dt>position</dt><dd>Type: System.Drawing.Point<br />A Point that indicates the start position of the text to blink. 

X specifies the column, Y the row.</dd><dt>length</dt><dd>Type: System.Int32<br />The length of the text (or cells) to blink.</dd><dt>interval</dt><dd>Type: System.TimeSpan<br />The blink interval.</dd><dt>count</dt><dd>Type: System.Int32<br />The amount of times to blink the text.</dd></dl>

#### Return Value
Type: CancellationTokenSource<br />A CancellationTokenSource object which you can use it to stop the blink at any time.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pos As New Point(10, 2)
Dim str As String = "Hello World!"

Console.SetCursorPosition(pos.X, pos.Y)
Console.Write(str)

' Start blinking the text written.
Dim len As Integer = str.Length
Dim interval As TimeSpan = TimeSpan.FromMilliseconds(500)
Dim count As Integer = 10
ConsoleTextBlink(pos, len, interval, count)

' Terminate program.
Console.ReadKey(intercept:=False)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_ConsoleTextBlink">ConsoleTextBlink Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />