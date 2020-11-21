# ServiceDependancyDisabledException Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException">ServiceDependancyDisabledException</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Exceptions">DevCase.Core.Shell.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ServiceDependancyDisabledException(
	ServiceController service,
	ServiceController dependancyService = null
)
```

**VB**<br />
``` VB
Public Sub New ( 
	service As ServiceController,
	Optional dependancyService As ServiceController = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim service As ServiceController
Dim dependancyService As ServiceController

Dim instance As New ServiceDependancyDisabledException(service, 
	dependancyService)
```

**C++**<br />
``` C++
public:
ServiceDependancyDisabledException(
	ServiceController^ service, 
	ServiceController^ dependancyService = nullptr
)
```

**F#**<br />
``` F#
new : 
        service : ServiceController * 
        ?dependancyService : ServiceController 
(* Defaults:
        let _dependancyService = defaultArg dependancyService null
*)
-> ServiceDependancyDisabledException
```


#### Parameters
&nbsp;<dl><dt>service</dt><dd>Type: System.ServiceProcess.ServiceController<br />\[Missing <param name="service"/> documentation for "M:DevCase.Core.Shell.Exceptions.ServiceDependancyDisabledException.#ctor(System.ServiceProcess.ServiceController,System.ServiceProcess.ServiceController)"\]</dd><dt>dependancyService (Optional)</dt><dd>Type: System.ServiceProcess.ServiceController<br />\[Missing <param name="dependancyService"/> documentation for "M:DevCase.Core.Shell.Exceptions.ServiceDependancyDisabledException.#ctor(System.ServiceProcess.ServiceController,System.ServiceProcess.ServiceController)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException">ServiceDependancyDisabledException Class</a><br /><a href="N_DevCase_Core_Shell_Exceptions">DevCase.Core.Shell.Exceptions Namespace</a><br />