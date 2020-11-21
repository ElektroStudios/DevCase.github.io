# AppConfig.PerformanceCountersEnabled Property 
 

Determines whether the performance counters feature is enabled in the application configuration file (app.config) of the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool PerformanceCountersEnabled { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property PerformanceCountersEnabled As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = AppConfig.PerformanceCountersEnabled

```

**C++**<br />
``` C++
public:
static property bool PerformanceCountersEnabled {
	bool get ();
}
```

**F#**<br />
``` F#
static member PerformanceCountersEnabled : bool with get

```


#### Property Value
Type: Boolean<br />Returns `false` (`False` in Visual Basic) if the performance counters feature is disabled or if the "`system.net`" section is not defined; otherwise, `true` (`True` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim enabled As Boolean = PerformanceCountersEnabled
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_Tools_AppConfig">AppConfig Class</a><br /><a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools Namespace</a><br />