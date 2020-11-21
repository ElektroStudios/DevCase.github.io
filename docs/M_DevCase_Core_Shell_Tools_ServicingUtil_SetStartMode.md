# ServicingUtil.SetStartMode Method (ServiceController, ServiceStartModeEx)
 

Sets the start mode of a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetStartMode(
	ServiceController svc,
	ServiceStartModeEx startMode
)
```

**VB**<br />
``` VB
Public Shared Sub SetStartMode ( 
	svc As ServiceController,
	startMode As ServiceStartModeEx
)
```

**VB Usage**<br />
``` VB Usage
Dim svc As ServiceController
Dim startMode As ServiceStartModeExServicingUtil.SetStartMode(svc, startMode)
```

**C++**<br />
``` C++
public:
static void SetStartMode(
	ServiceController^ svc, 
	ServiceStartModeEx startMode
)
```

**F#**<br />
``` F#
static member SetStartMode : 
        svc : ServiceController * 
        startMode : ServiceStartModeEx -> unit 

```


#### Parameters
&nbsp;<dl><dt>svc</dt><dd>Type: System.ServiceProcess.ServiceController<br />The service.</dd><dt>startMode</dt><dd>Type: <a href="T_DevCase_Core_Shell_ServiceStartModeEx">DevCase.Core.Shell.ServiceStartModeEx</a><br />The start mode.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_ServicingUtil_SetStartMode">SetStartMode Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />