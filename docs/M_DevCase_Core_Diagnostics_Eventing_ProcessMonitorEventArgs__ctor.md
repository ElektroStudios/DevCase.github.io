# ProcessMonitorEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Diagnostics_Eventing_ProcessMonitorEventArgs">ProcessMonitorEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Eventing">DevCase.Core.Diagnostics.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ProcessMonitorEventArgs(
	int processId,
	string processName
)
```

**VB**<br />
``` VB
Public Sub New ( 
	processId As Integer,
	processName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim processId As Integer
Dim processName As String

Dim instance As New ProcessMonitorEventArgs(processId, 
	processName)
```

**C++**<br />
``` C++
public:
ProcessMonitorEventArgs(
	int processId, 
	String^ processName
)
```

**F#**<br />
``` F#
new : 
        processId : int * 
        processName : string -> ProcessMonitorEventArgs
```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.Int32<br />The process id (PID) of the intercepted process.</dd><dt>processName</dt><dd>Type: System.String<br />The name of the intercepted process.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Eventing_ProcessMonitorEventArgs">ProcessMonitorEventArgs Class</a><br /><a href="N_DevCase_Core_Diagnostics_Eventing">DevCase.Core.Diagnostics.Eventing Namespace</a><br />