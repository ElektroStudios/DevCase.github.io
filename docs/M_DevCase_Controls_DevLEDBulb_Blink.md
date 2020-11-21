# DevLEDBulb.Blink Method 
 

Causes the Led to start blinking

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Blink(
	int milliseconds
)
```

**VB**<br />
``` VB
Public Overridable Sub Blink ( 
	milliseconds As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDBulb
Dim milliseconds As Integer

instance.Blink(milliseconds)
```

**C++**<br />
``` C++
public:
virtual void Blink(
	int milliseconds
)
```

**F#**<br />
``` F#
abstract Blink : 
        milliseconds : int -> unit 
override Blink : 
        milliseconds : int -> unit 
```


#### Parameters
&nbsp;<dl><dt>milliseconds</dt><dd>Type: System.Int32<br />Number of milliseconds to blink for. 0 stops blinking</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDBulb">DevLEDBulb Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />