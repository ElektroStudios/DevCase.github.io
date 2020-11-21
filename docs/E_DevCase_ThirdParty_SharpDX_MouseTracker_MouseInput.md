# MouseTracker.MouseInput Event
 

Event raised when device muting changes.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MouseInputEventArgs> MouseInput
```

**VB**<br />
``` VB
Public Event MouseInput As EventHandler(Of MouseInputEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseTracker
Dim handler As EventHandler(Of MouseInputEventArgs)

AddHandler instance.MouseInput, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MouseInputEventArgs^>^ MouseInput {
	void add (EventHandler<MouseInputEventArgs^>^ value);
	void remove (EventHandler<MouseInputEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member MouseInput : IEvent<EventHandler<MouseInputEventArgs>,
    MouseInputEventArgs>

```


#### Value
Type: System.EventHandler(MouseInputEventArgs)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SharpDX_MouseTracker">MouseTracker Class</a><br /><a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX Namespace</a><br />