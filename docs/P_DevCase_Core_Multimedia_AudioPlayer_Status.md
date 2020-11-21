# AudioPlayer.Status Property 
 

Gets the current player State.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual PlayerStatus Status { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Status As PlayerStatus
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim value As PlayerStatus

value = instance.Status

```

**C++**<br />
``` C++
public:
virtual property PlayerStatus Status {
	PlayerStatus get ();
}
```

**F#**<br />
``` F#
abstract Status : PlayerStatus with get
override Status : PlayerStatus with get
```


#### Property Value
Type: <a href="T_DevCase_Core_Multimedia_PlayerStatus">PlayerStatus</a><br />The current player State.

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />