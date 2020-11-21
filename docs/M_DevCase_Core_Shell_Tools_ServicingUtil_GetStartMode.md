# ServicingUtil.GetStartMode Method (ServiceController)
 

Gets the start mode of a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ServiceStartModeEx GetStartMode(
	ServiceController svc
)
```

**VB**<br />
``` VB
Public Shared Function GetStartMode ( 
	svc As ServiceController
) As ServiceStartModeEx
```

**VB Usage**<br />
``` VB Usage
Dim svc As ServiceController
Dim returnValue As ServiceStartModeEx

returnValue = ServicingUtil.GetStartMode(svc)
```

**C++**<br />
``` C++
public:
static ServiceStartModeEx GetStartMode(
	ServiceController^ svc
)
```

**F#**<br />
``` F#
static member GetStartMode : 
        svc : ServiceController -> ServiceStartModeEx 

```


#### Parameters
&nbsp;<dl><dt>svc</dt><dd>Type: System.ServiceProcess.ServiceController<br />The service.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Shell_ServiceStartModeEx">ServiceStartModeEx</a><br />The service's start mode.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_ServicingUtil_GetStartMode">GetStartMode Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />