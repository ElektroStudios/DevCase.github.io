# PowerUtil.PowerPlans Property 
 

Gets all the power plans available on the current system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<PowerPlan> PowerPlans { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property PowerPlans As ReadOnlyCollection(Of PowerPlan)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of PowerPlan)

value = PowerUtil.PowerPlans

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<PowerPlan^>^ PowerPlans {
	ReadOnlyCollection<PowerPlan^>^ get ();
}
```

**F#**<br />
``` F#
static member PowerPlans : ReadOnlyCollection<PowerPlan> with get

```


#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_Core_Shell_PowerPlan">PowerPlan</a>)<br />The active power plan.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />