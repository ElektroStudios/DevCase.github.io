# NetworkUtil.IsNetworkAvailable Property 
 

Gets a value indicating whether at least one of the current network adapters is capable of connecting to Internet.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsNetworkAvailable { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property IsNetworkAvailable As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = NetworkUtil.IsNetworkAvailable

```

**C++**<br />
``` C++
public:
static property bool IsNetworkAvailable {
	bool get ();
}
```

**F#**<br />
``` F#
static member IsNetworkAvailable : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if at least one of the current network adapters is capable of connecting to Internet; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />