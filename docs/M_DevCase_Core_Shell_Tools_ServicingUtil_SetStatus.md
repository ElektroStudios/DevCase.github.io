# ServicingUtil.SetStatus Method (ServiceController, ServiceStatus, Boolean, Boolean)
 

Sets the status of a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetStatus(
	ServiceController svc,
	ServiceStatus status,
	bool wait = false,
	bool throwOnStatusMissmatch = false
)
```

**VB**<br />
``` VB
Public Shared Sub SetStatus ( 
	svc As ServiceController,
	status As ServiceStatus,
	Optional wait As Boolean = false,
	Optional throwOnStatusMissmatch As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim svc As ServiceController
Dim status As ServiceStatus
Dim wait As Boolean
Dim throwOnStatusMissmatch As BooleanServicingUtil.SetStatus(svc, status, wait, 
	throwOnStatusMissmatch)
```

**C++**<br />
``` C++
public:
static void SetStatus(
	ServiceController^ svc, 
	ServiceStatus status, 
	bool wait = false, 
	bool throwOnStatusMissmatch = false
)
```

**F#**<br />
``` F#
static member SetStatus : 
        svc : ServiceController * 
        status : ServiceStatus * 
        ?wait : bool * 
        ?throwOnStatusMissmatch : bool 
(* Defaults:
        let _wait = defaultArg wait false
        let _throwOnStatusMissmatch = defaultArg throwOnStatusMissmatch false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>svc</dt><dd>Type: System.ServiceProcess.ServiceController<br />The service.</dd><dt>status</dt><dd>Type: <a href="T_DevCase_Core_Shell_ServiceStatus">DevCase.Core.Shell.ServiceStatus</a><br />The target service status.</dd><dt>wait (Optional)</dt><dd>Type: System.Boolean<br />if set to `true` (`True` in Visual Basic) waits for the status change completition.</dd><dt>throwOnStatusMissmatch (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), throws an error when attempting to start a service that is started, or attempting to stop a service that is stopped.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_ServicingUtil_SetStatus">SetStatus Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />