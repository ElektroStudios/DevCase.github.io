# WindowInfo.ThreadId Property 
 

Gets the identifier of the thread that created this window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ThreadId { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ThreadId As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo
Dim value As Integer

value = instance.ThreadId

```

**C++**<br />
``` C++
public:
property int ThreadId {
	int get ();
}
```

**F#**<br />
``` F#
member ThreadId : int with get

```


#### Property Value
Type: Int32<br />\[Missing <value> documentation for "P:DevCase.Core.IPC.WindowInfo.ThreadId"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />