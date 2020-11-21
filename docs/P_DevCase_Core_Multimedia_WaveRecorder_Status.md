# WaveRecorder.Status Property 
 

Gets the current recording status.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual RecorderStatus Status { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Status As RecorderStatus
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As WaveRecorder
Dim value As RecorderStatus

value = instance.Status

```

**C++**<br />
``` C++
public:
virtual property RecorderStatus Status {
	RecorderStatus get ();
}
```

**F#**<br />
``` F#
abstract Status : RecorderStatus with get
override Status : RecorderStatus with get
```


#### Property Value
Type: <a href="T_DevCase_Core_Multimedia_RecorderStatus">RecorderStatus</a><br />The current recording status.

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_WaveRecorder">WaveRecorder Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />