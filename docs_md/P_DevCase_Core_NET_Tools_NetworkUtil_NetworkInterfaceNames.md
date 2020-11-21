# NetworkUtil.NetworkInterfaceNames Property 
 

Gets the current network interface names.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> NetworkInterfaceNames { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property NetworkInterfaceNames As IEnumerable(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As IEnumerable(Of String)

value = NetworkUtil.NetworkInterfaceNames

```

**C++**<br />
``` C++
public:
static property IEnumerable<String^>^ NetworkInterfaceNames {
	IEnumerable<String^>^ get ();
}
```

**F#**<br />
``` F#
static member NetworkInterfaceNames : IEnumerable<string> with get

```


#### Property Value
Type: IEnumerable(String)<br />An IEnumerable(T) that enumerates the network interface names.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />