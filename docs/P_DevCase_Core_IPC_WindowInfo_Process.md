# WindowInfo.Process Property 
 

Gets the identifier of the process that created this window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Process Process { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Process As Process
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo
Dim value As Process

value = instance.Process

```

**C++**<br />
``` C++
public:
property Process^ Process {
	Process^ get ();
}
```

**F#**<br />
``` F#
member Process : Process with get

```


#### Property Value
Type: Process<br />\[Missing <value> documentation for "P:DevCase.Core.IPC.WindowInfo.Process"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />