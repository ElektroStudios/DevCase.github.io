# ProcessMonitorEventArgs.ProcessId Property 
 

Gets the process id (PID) of the intercepted process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Eventing">DevCase.Core.Diagnostics.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ProcessId { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ProcessId As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessMonitorEventArgs
Dim value As Integer

value = instance.ProcessId

```

**C++**<br />
``` C++
public:
property int ProcessId {
	int get ();
}
```

**F#**<br />
``` F#
member ProcessId : int with get

```


#### Property Value
Type: Int32<br />The process id (PID) of the intercepted process.

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Eventing_ProcessMonitorEventArgs">ProcessMonitorEventArgs Class</a><br /><a href="N_DevCase_Core_Diagnostics_Eventing">DevCase.Core.Diagnostics.Eventing Namespace</a><br />