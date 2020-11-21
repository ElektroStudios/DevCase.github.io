# ProcessMonitorEventArgs.ProcessName Property 
 

Gets the name of the intercepted process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Eventing">DevCase.Core.Diagnostics.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ProcessName { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ProcessName As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessMonitorEventArgs
Dim value As String

value = instance.ProcessName

```

**C++**<br />
``` C++
public:
property String^ ProcessName {
	String^ get ();
}
```

**F#**<br />
``` F#
member ProcessName : string with get

```


#### Property Value
Type: String<br />The name of the intercepted process.

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Eventing_ProcessMonitorEventArgs">ProcessMonitorEventArgs Class</a><br /><a href="N_DevCase_Core_Diagnostics_Eventing">DevCase.Core.Diagnostics.Eventing Namespace</a><br />