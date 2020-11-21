# PowerUtil.ActivePowerPlan Property 
 

Gets or sets the active power plan on the current system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PowerPlan ActivePowerPlan { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ActivePowerPlan As PowerPlan
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As PowerPlan

value = PowerUtil.ActivePowerPlan

PowerUtil.ActivePowerPlan = value
```

**C++**<br />
``` C++
public:
static property PowerPlan^ ActivePowerPlan {
	PowerPlan^ get ();
	void set (PowerPlan^ value);
}
```

**F#**<br />
``` F#
static member ActivePowerPlan : PowerPlan with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Shell_PowerPlan">PowerPlan</a><br />The active power plan.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />