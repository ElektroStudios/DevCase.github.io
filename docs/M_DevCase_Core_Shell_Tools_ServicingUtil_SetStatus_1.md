# ServicingUtil.SetStatus Method (String, ServiceStatus, Boolean, Boolean)
 

Sets the status of a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetStatus(
	string svcName,
	ServiceStatus status,
	bool wait = false,
	bool throwOnStatusMissmatch = false
)
```

**VB**<br />
``` VB
Public Shared Sub SetStatus ( 
	svcName As String,
	status As ServiceStatus,
	Optional wait As Boolean = false,
	Optional throwOnStatusMissmatch As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim svcName As String
Dim status As ServiceStatus
Dim wait As Boolean
Dim throwOnStatusMissmatch As BooleanServicingUtil.SetStatus(svcName, status, wait, 
	throwOnStatusMissmatch)
```

**C++**<br />
``` C++
public:
static void SetStatus(
	String^ svcName, 
	ServiceStatus status, 
	bool wait = false, 
	bool throwOnStatusMissmatch = false
)
```

**F#**<br />
``` F#
static member SetStatus : 
        svcName : string * 
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
&nbsp;<dl><dt>svcName</dt><dd>Type: System.String<br />The service name.</dd><dt>status</dt><dd>Type: <a href="T_DevCase_Core_Shell_ServiceStatus">DevCase.Core.Shell.ServiceStatus</a><br />The target service status.</dd><dt>wait (Optional)</dt><dd>Type: System.Boolean<br />if set to `true` (`True` in Visual Basic) waits for the status change completition.</dd><dt>throwOnStatusMissmatch (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), throws an error when attempting to start a service that is started, or attempting to stop a service that is stopped.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Any service found with the specified name.;svcName</td></tr><tr><td><a href="T_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException">ServiceDependancyDisabledException</a></td><td>Cannot start service because a dependant service is disabled.</td></tr><tr><td>Exception</td><td>Cannot start or stop service because it is disabled. or The service is already running or pendng to run it. or The service is already stopped or pendng to stop it.</td></tr><tr><td>InvalidEnumArgumentException</td><td>status</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Servicing.SetStatus("themes", ServiceStatus.Stop, wait:=True, throwOnStatusMissmatch:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_ServicingUtil_SetStatus">SetStatus Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />