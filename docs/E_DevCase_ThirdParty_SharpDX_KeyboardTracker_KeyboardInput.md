# KeyboardTracker.KeyboardInput Event
 

Occurs when they keyboard sends input.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<KeyboardInputEventArgs> KeyboardInput
```

**VB**<br />
``` VB
Public Event KeyboardInput As EventHandler(Of KeyboardInputEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardTracker
Dim handler As EventHandler(Of KeyboardInputEventArgs)

AddHandler instance.KeyboardInput, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<KeyboardInputEventArgs^>^ KeyboardInput {
	void add (EventHandler<KeyboardInputEventArgs^>^ value);
	void remove (EventHandler<KeyboardInputEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member KeyboardInput : IEvent<EventHandler<KeyboardInputEventArgs>,
    KeyboardInputEventArgs>

```


#### Value
Type: System.EventHandler(KeyboardInputEventArgs)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SharpDX_KeyboardTracker">KeyboardTracker Class</a><br /><a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX Namespace</a><br />