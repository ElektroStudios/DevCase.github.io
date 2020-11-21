# WindowInfo.DeviceContext Property 
 

Gets a handle to a device context (DC) for this window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr DeviceContext { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property DeviceContext As IntPtr
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo
Dim value As IntPtr

value = instance.DeviceContext

```

**C++**<br />
``` C++
public:
property IntPtr DeviceContext {
	IntPtr get ();
}
```

**F#**<br />
``` F#
member DeviceContext : IntPtr with get

```


#### Property Value
Type: IntPtr<br />\[Missing <value> documentation for "P:DevCase.Core.IPC.WindowInfo.DeviceContext"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />