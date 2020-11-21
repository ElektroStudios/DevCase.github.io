# ProfillingUtil.InvokeTimes Method (Int32, Action)
 

Invokes an Action for the specified amount of times.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InvokeTimes(
	int count,
	Action action
)
```

**VB**<br />
``` VB
Public Shared Sub InvokeTimes ( 
	count As Integer,
	action As Action
)
```

**VB Usage**<br />
``` VB Usage
Dim count As Integer
Dim action As ActionProfillingUtil.InvokeTimes(count, action)
```

**C++**<br />
``` C++
public:
static void InvokeTimes(
	int count, 
	Action^ action
)
```

**F#**<br />
``` F#
static member InvokeTimes : 
        count : int * 
        action : Action -> unit 

```


#### Parameters
&nbsp;<dl><dt>count</dt><dd>Type: System.Int32<br />The amount of times to execute the funtion.</dd><dt>action</dt><dd>Type: System.Action<br />The Action to be executed.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_ProfillingUtil">ProfillingUtil Class</a><br /><a href="Overload_DevCase_Core_Diagnostics_Tools_ProfillingUtil_InvokeTimes">InvokeTimes Overload</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />